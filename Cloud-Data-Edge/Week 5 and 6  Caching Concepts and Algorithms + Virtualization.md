
 [[ELEC0137 Cloud, Data Centres and Edge Computing]]
# Lecture 1: Virtualisation
- #### Introduction 
- Operating system outline: The software managing the hardware on a computer
- --> design system for handling the hardware, process systems and resource management

- Abstraction, isolation, protection, robustness required. Linux kernel provides these. 
- 
This is how we review any sections:
### Storage: The file Abstraction:
- files and directories are mapped entirely to blocks within memory that live on the Disk. This is an abstraction.
- This level of layering allows calls to the OS to open,read,write etc... 
- This is slower, but it is safer. 
- The file directory maps everything in the disk that lets you know what file is where. This is how it determines what is being utilised. 
### Processing: The process Abstraction:
- Processing is the action of the code being executing on the cpu. 
- This process is done by syscalls. 
- A process is made up of 1 or more threads, and then the scheduler determines by priority which is to be used at the moment
### User-Mode/Kernel-Mode:
- 2 modes within an OS: User-mode and Kernel-mode
- Typically there will be a register bitmap to recognise in hardware whether something is being run in kernel-mode or in user-mode. This determines what is being executed. Some intructions are handled in root. 
	- N.B. Some intructions are privileged and are only executed in kernel mode. 
	- A system call can change kernel mode then return and reset it to user mode.
- Kernel code: 
	- In particular (interrupt handlers):
	- HW allows machine instructions to be executed and allows unrestricted access to memory and I/O ports. Everything else runs in user mode.
- The only way to access this typically is through a syscall. The OS relies heavily on hardware-enforced protection mechanism.

### Resource management:
- Operating system are responsible for management of shared hardware resources. 
- Isolation of users and process + utilize resources whenever work is required is highest priority
- Operating system use process abstraction for isolation to prevent malicious users (in case system is compromised)
- This is especially difficult for large scale systems like cloud or edge cloud computing with lots of users and resources

### Resource management in cloud:
- To prevent all issues in cloud (i.e: hacking or issues):
- Virtualization is utilized. It provides abstraction to the the system and is another isolation mechanism. It simplifies the management of the physical resources through a "virtual machine" abstraction. 
- This is **fundamental** to Cloud Computing

##### Layering Principles:
- The layering is how we review the user of interfaces and calls within a system: 
- i.e: API--> ABI --> ISA --> syscalls
#### Operating System & Virtualisation Overview
- **Summary of Operating System Concepts**
- **System Resource Management**
- **Layering and Virtualisation**
- **Virtualisation Techniques**
- **Virtual Machine (VM)**
- **Containers**
- **Unikernel**
- **VM Migration**
- **Edge Computing and Virtualisation**

#### Virtual Machines
- A VM is an abstraction: it's an isolated environment that is an abstract layer that communicates to some remote system. It's a method to run a platform-independent host for a single application VM.
- It's a "container" that runs its own indepdent system within the OS. 
- Is an isolated environment that appears to be a whole computer • In reality, it only has access to a portion of the computer resources
There are 3 types of VM:
1) System VM: Runs as a complete system, with it's own VM which can run multiple applications
2) A process VM is a virtual platform created for an indvidual process and destroyed once the process terminates. Every application running on a machine has its own process VM to handle it.
3) Application VM: The VM is running under the control of a normal VM and provides a platform indepdent host for a single application: i.e; Java virtual machine

#### Virtual Machine monitor (VMM/Hypervisor)
- Partitions the 