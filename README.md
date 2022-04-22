# inspection-plc

Control Code for the Omron PLC and related software.

### Usage
Add usage instructions.

### Setup Requirements
These tools interface with Omron's Sysmac Studio Software. Learn more here: https://automation.omron.com/en/us/products/family/sysstdio

### Control System
AFRL_Capstone_ControlLoop is the most up-to-date version of the control system. 
This is configured for a different model PLC than the one the project is set to use. 
To run on the NX102 PLC system, make sure to change the device configuration within Sysmac Studio.

### Serial Setup Template
If for any reason issues arise with serial communications, use OSU_Capstone_PI_Control as a template for a new project file.
You can disregard the "Auto" program and create a new program to house the control system. 
