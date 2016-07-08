# tmssh - To Many SSH
A script for keeping track of all your remote ssh servers. I personally have to ssh into WAY to many remote servers, and this script eases that process.

## Install
```bash
git clone git@github.com:V-FEXrt/tmssh.git
cd tmssh
cp tmssh /usr/local/bin # Any other location in your path is also acceptable 
```

## Usage
```bash
tmssh add user@remote.server.com myserver # Adds myserver to the list of saved servers
tmssh myserver # ssh into user@remote.server.com
tmssh list # List all server names
tmshh list -l # List all server names and their address
tmshh remove myserver # Remove myserver from the list of saved servers
tmshh help # print help
tmshh version # print version info
```
