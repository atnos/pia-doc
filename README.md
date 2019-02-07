# pia-doc

## How to use the "Open Virtual Appliance" file

- Download the file https://github.com/atnos/pia-doc/blob/master/pia-back_2.0.1.ova
- Import the appliance file inside VirtualBox (or VMWare)
- On the "settings" menu select the "Network" folder
- Enable the Network Adapter, select "Bridged Adapter" and select the "Name" corresponding to your network interface
- Start the VM
  - login: pia
  - Password: piapia (You must change it)
- Find your IP address : `ip a`
- Go to the pia-back folder `cd pia-back`
- Start the rails server `bin/rails s`

See https://github.com/LINCnil/pia-back#run-the-application-in-production-mode if you want to use it in production mode.
