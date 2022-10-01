# picoder (deprecated)
Hard Fork of the deprecated [picorder](https://github.com/directive0/picorderOS)

### Purpose: 

Explore a 3 layer softeware stack.
- Presentation Layer - Displays, graphs, lights, sound
- Logic layer - Drivers, switches, timers
- Data Layer - logs, status, and arrays

Why: 
Flexability.
- increase sensor compatibility 
-  
- Plug in and play for i2c devices
- Decrease base file size and line count


An evirmental scanner

# Requiered
- Raspberry Pi
  - sensors - one of the following
    - [list](https://gitlab.com/tearran/its-i2cDevices) of avalible i2cdevices   

## Done
 
 #### Data:
  - Standardize sensor values
  
  - passing os system values
 #### Logic
  - error handeling
    - clean exit with keyboard interupt
    - report "0" value on sensor error. todo verbose mode 
  - bash pipes [Scripts ](https://gitlab.com/tearran/its-i2cDevices)
  


## Looking into:
- ~upateing to python3~ working 
- remove pip library dependence.  
  - packeage and deploy 
  - vanilla option offers builtin support for reliable security updates 
- data 
   - read sqlite3
   - write sqlite3 


## Requirements:
Changing in development

## Sources
This project was made possible by information and inspiration provided by these sources:
- https://github.com/directive0/picorder
- https://github.com/tearran/
- more to come
