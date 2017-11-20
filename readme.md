Ansible play book to install Docker on the nvidia TX2

1. Setup the TX2 as normal using JetPack L4T 3.0 (3.1 not currently working)
2. Setup networking on the TX2
3. Install Ansible on a linux based system other than the TX2

Then run start.sh
The script assumes default settings on the TX2 and that it is reachable by pinging tegra-ubuntu.local
