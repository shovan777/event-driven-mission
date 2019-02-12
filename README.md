# Dronekit implementation of event driven code
- this code currently flies the drone in a square region of about 10m 

## Dependencies
- install conda
```bash
conda env create -f environment.yml
```
## Run the code for simulation or in pixhawk hardware as
```bash
python square_flyer.py /dev/ttyACM0
```