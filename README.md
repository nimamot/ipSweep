# IPSweep
A bash script that performs an IP sweep to find active hosts on a network.

## Usage
./ipsweep.sh [network_prefix]


### Example
./ipsweep.sh 192.168.1



## Description
This script takes in the network prefix as an argument and performs a ping sweep by pinging all the possible IP addresses within the network range. If a host is active, it will respond to the ping and the script will output the IP address of that host.

## Prerequisites
- A Unix-based system with `bash` shell
- `ping` command installed

## Notes
- If no argument is provided, the script will prompt you to enter the network prefix.
- The script requires elevated privileges to run the `ping` command.
