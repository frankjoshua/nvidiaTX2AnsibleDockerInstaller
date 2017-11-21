# Ansible playbook to install Docker on the nvidia TX2

1. Setup the TX2 as normal using JetPack L4T 3.0 (3.1 not currently working)
2. Setup networking on the TX2
3. Install Ansible on a linux based system other than the TX2

Then run `start.sh`
The script assumes default settings on the TX2 and that it is reachable by pinging tegra-ubuntu.local

## Optional Steps
The default version of docker is old. You may want to update to a newer version. These methods change but as of the time of this writing this worked.
Download and install docker-ce from https://docs.docker.com/engine/installation/linux/docker-ce/binaries
The install docker-compose using pip
```
sudo apt-get remove docker-compose
sudo apt-get install python-pip
sudo pip install setuptools
sudo pip install docker-compose
```
