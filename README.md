# SAFEWALK-SENSOR
#       Project lead: Prof.N.Sudha
#       Developers: Ashwin.R(B.Tech ECE),Venkatesh(M.Tech AI-DS)
# Can run in any operating system 
* Better to run in linux mint if not there install linux mint in virtual box

# Linux mint installation 
* Refer: https://itsfoss.com/install-linux-mint-in-virtualbox/

# Installation of Python on linux mint:
* open terminal
* sudo apt update
* sudo apt install software-properties-common
* sudo add-apt-repository ppa:deadsnakes/ppa
* sudo apt install python3.9

# Installation procedure of cli
* open new terminal
* curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
* sudo apt-get install -y nodejs
* node -v
* npm config get prefix
* mkdir ~/.npm-global
* npm config set prefix '~/.npm-global'
* echo 'export PATH=~/.npm-global/bin:$PATH' >> ~/.profile
* npm install -g edge-impulse-cli

# final 
* sudo apt install screen

# Connect the optional camera, sensor, extension board, Wi-Fi add-ons, and SD card

# Connect the development board to your computer
* Use a micro-USB cable to connect the main development board (not the extension board) to your computer.

# Update the bootloader and the firmware
* Download the latest Edge Impulse firmware(under initial firmware folder), and unzip the file.
* Open the flash script for your operating system (flash_linux.sh) to flash the firmware.
* Wait until flashing is complete. The on-board LEDs should stop blinking to indicate that the new firmware is running.
* From a terminal, run: edge-impulse-daemon (enter your edge impulse login credentials)

# Run .sh file(under safewalk firmware folder)
* select the board

# Open new terminal
* run: edge-impulse-run-impulse --continuous
