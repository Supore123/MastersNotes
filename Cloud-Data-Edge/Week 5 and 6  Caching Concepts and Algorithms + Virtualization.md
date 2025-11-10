
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