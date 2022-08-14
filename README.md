# .node-red

The directory contains configuration files for running with a node-red server.

This directory should be pasted or replace in:
* windows: c:/Users/[username]/.node-red
* ubuntu: /root/.node-red    (according to the installation through cloning node-red from its repo https://github.com/node-red/node-red)

## Technologies
Project is created with:

* nvm 
  - node 15.5.0
    - node-red:
         git clone https://github.com/node-red/node-red.git
         cd node-red
         npm install
         npm run build
         npm start -- flows_[computer_name].json --port 80
         
## About Node-red:
 
Node-RED software is the core of this project, it is an open-source IOT project (https://nodered.org/).
It can be released in a cloud server and can support HTTP requests and send MQTT messages to connected microcontrollers.


## flows_DESKTOP-SQFDK9G.json:
Configuration file that contains flow for controlling a bulb light remotely.


## flows_jhonServer.json:
Configuration file that contains flow for interacting with the project https://github.com/JhonVelasquez/esp32_woki_node-red
Receives and sends information to the ESP32 microcontroller that executes the code that is in the esp32_woki_node-red project





