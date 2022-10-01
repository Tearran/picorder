# Enviro scanner. Name TBD
This software is in heavy development 

Hard Fork of the deprecated [picorder](https://github.com/directive0/picorderOS)


An evirmental scanner

# Requiered
- Raspberry Pi
  - sensors - one of the following
    - [list](https://gitlab.com/tearran/its-i2cDevices) of avalible i2cdevices   

## Done
- Standardize sensor value retrieval through
  - [list](https://gitlab.com/tearran/its-i2cDevices) bash pipes
  - passing os system values
- data 
   - read sqlite
   - write sqlite 


## Looking into:
- upateing to python3
- remove pip library dependence.  
  - packeage and deploy 
  - vanilla option offers builtin support for reliable security updates 
- error handeling
   - clean exit with keyboard interup
   - clean exit with gpio button press
   - Report prompt possible fix
    example from [its_sensehat.py](https://gitlab.com/tearran/its-senseHat)
    ```bash
    import sys # built-in mod

    try:
      from sense_hat1 import SenseHat
    except ModuleNotFoundError:
      print("can not fint sense-hat try;")
      print("\tsudo apt install sense-hat")
      sys.exit()
       
    ```   
## Requirements:
Changing in development

## Sources
This project was made possible by information and inspiration provided by these sources:
- https://github.com/directive0/picorder
