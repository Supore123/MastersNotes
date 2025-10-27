
**Course:** [[ELEC0152: Advanced Embedded IOT]]
**Date:** 2025-10-27
**Source:** [Lecture Slides](url)

---

## 🧩 Key Concepts
- Requirements for schematic design listed
- Current idea template is to copy HM design, alternate for usage to a difference type of device, instead can have an ESP32 on the device to produce it's own wifi network capabilities
- List the requirements later on for the usage

-- This is a list of fair comparison points for usage, I don't have the time or capacity to follow through on it. This is an unfair use. 

### Component listing

###### Requirements:
- MCU: Either STM32u585 or Silabs Based MCU, could consider using their AI units for logging data, could be some kind of recogniser unit. 
- External Flash: Requirement needed as listed on their component point --> This can be with the SST25 flash use
- Have an external RTC to maintain second level precision based on clock drift, this is important for a battery type device. i.e: the RXC130
- External radio module: Could be the Hope RF and/or the on the device MCU antenna to perform the OTA and send signals. Or this can be uploaded via USB instead. This can be handled via the DMA between the devices. 


N.B. Might need to download the external files to be able to add to it successful
-- I am not concerned about their wellbeing at this point -- why is man trying to get onto me. I g
## 🔗 Related Topics
- [[Neural Networks]]
