# Virtual CAN bus with Carla simulator

# Dependencies (What I'm using):

## python 3.7.10
## carla simulator version 0.9.9 (https://carla.readthedocs.io/en/0.9.9/)
## cantools 36.2.0 (pip install cantools)
## python-can3.3.4 (pip install python-can)
## CANdevStudio (https://github.com/GENIVI/CANdevStudio)

# Run the "vcan.sh" file in the terminal with the following command: 
## ./vcan.sh

# Install CARLA and check for the installation in the /opt/ folder.

## sudo apt-get update
## sudo apt-get install carla-simulator
## cd /opt/carla-simulator

# Running CARLA

## cd bin
## ./CarlaUE4.sh

# Put the files that are inside the "files_for_Carla_simulator" folder inside the carla directory "/opt/carla-simulator/PythonAPI/examples" 
# Run the Carla client
## python modified_client_v2.py 

# See the video below for more details and also how to use CANdevStudio to send CAN bus messages:
