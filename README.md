# RPi-Cam-Web-Interface
RPi Cam Web Interface is a web interface for the Raspberry Pi Camera module.

## Installation Instruction

### Step 1: Install Raspbian on your RPi

### Step 2: Attach camera to RPi and enable camera support (http://www.raspberrypi.org/camera)

### Step 3: Update your RPi with the following commands:

    $ sudo apt-get update
    $ sudo apt-get dist-upgrade

### Step 4: Clone the code from github and enable and run the install script with the following commands:

    $ git clone https://github.com/silvanmelchior/RPi_Cam_Web_Interface.git
    $ cd RPi_Cam_Web_Interface
    $ ./install.sh

The scripts are

    - install.sh main installation as used in step 4 above
    - update.sh check for updates and then run main installation
    - start.sh starts the software. If already running it restarts.
    - stop.sh stops the software
    - remove.sh removes the software
    - debug.sh is same as start but allows raspimjpeg output to console for debugging
    - To run these scripts make sure you are in the RPi_Cam_Web_Interface folder then precede the script with a ./
    - E.g. To update an existing installation ./update.sh
    - E.g. To start the camera software ./start.sh
    - E.g. To stop the camera software ./stop.sh

### Step 5: Use it

Open up any browser on any computer in your network and enter the url to access the camera web site.
 
 
 for more info
 
    https://elinux.org/RPi-Cam-Web-Interface
