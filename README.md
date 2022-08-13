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

