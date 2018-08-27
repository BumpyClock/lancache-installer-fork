# Do not use - Under development lancache-installer

# Forked from nexusofdoom with tweaks for my own personal network environment, please use with care.
Installer for the [lancache](https://github.com/zeropingheroes/lancache) by [nexusofdoom](https://github.com/nexusofdoom) and [Zero Ping Heroes](https://github.com/zeropingheroes)
 
 ##### Install Debian 9.4 X64 with SSH and Endable sudo
 ##### Testing Ubuntu 18.04.1 with SSH run scripts as sudo.
 
 ##### Download url for debian:
  https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/debian-9.4.0-amd64-netinst.iso
 ##### Download url for Ubuntu 18.04.1 Server  
  http://cdimage.ubuntu.com/releases/18.04.1/release/ubuntu-18.04.1-server-amd64.iso
 
 ##### You will need 18 avaliable IP's example 192.168.0.2 - 192.168.0.20 used for lancache
 
 # Install git 
 
`apt-get install git`

# Clone the git repo
 
 `git clone -b master http://github.com/nexusofdoom/lancache-installer`
 
 `cd lancache-installer`
 
 `chmod +x *.sh`

# Run scripts as sudo or root user

### Run 
 
 `./install.sh`
 
### Next run
 
 `./install-jemalloc.sh`

### Then run 
 
 `./install-nginx.sh`

### After run 
 
 `./install-sniproxy.sh`

### Last run 
 
 `./install-lancache.sh`
 
#########################################################################

Working on 

change-network.sh	 an easy way to change your ip's for a new network

install-netdata.sh install a web gui to monitor performance of lancache.
