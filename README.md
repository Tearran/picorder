# picoder (deprecated)
Hard Fork of the deprecated [picorder](https://github.com/directive0/picorderOS)

### Purpose: 

Explore a 3 layer softeware stack.
- Presentation Layer - Displays, graphs, lights, sound
- Logic layer - Drivers, switches, timers
- Data Layer - logs, status, and arrays to Translate/bridge/cummunicate between layers.

Why: 
Flexability.
- increase sensor compatibility 
- Compatibility with node.js, perl, php, c, so on and ... 
- Plug in and play for i2c devices
- Decrease base file size and line count
- Most importantly to split tasks by instperation.
  - Creative - Work on Presentation Layer
  - Problem solving - Work on Logic layer
  - Research - work on Data Layer 

## Done
 
 #### Data:
  - Standardize sensor values
  - passing os system values
 #### Logic
  - error handeling
    - clean exit with keyboard interupt
    - report "0" value on sensor error. todo verbose mode 
  - remove requierment
    - psutil replaced with vanilla/build-in
  - compatible sensors  [Scripts ](https://gitlab.com/tearran/its-i2cDevices)
  
## Exploring:
- ~update to python3~ working 
- remove pip library dependence.  
  - packeage and deploy 
  - vanilla option offers builtin support for reliablilty, security and, updates 
- data 
   - read sqlite3
   - write sqlite3 

## Requirements:
Changing in development

## Sources
This project was made possible by information and inspirations:
- https://github.com/directive0/picorder
- https://github.com/tearran/
- more to come
