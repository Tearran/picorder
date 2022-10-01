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
- Plug in and play for i2c devices
- Decrease base file size and line count


An evirmental scanner

# Requiered
- Raspberry Pi
  - sensors - one of the following
    - [list](https://gitlab.com/tearran/its-i2cDevices) of avalible i2cdevices   

## Done
- data
  - Standardize sensor value retrieval through
  - [list](https://gitlab.com/tearran/its-i2cDevices) bash pipes
  - passing os system values
- error handeling
   - clean exit with keyboard interup


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
