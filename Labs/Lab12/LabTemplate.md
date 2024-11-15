## Lab 10

- Name:
- Email:

## Part 1 - Linux Network Command Cheat Sheet

- `hostname`
- `ifconfig`
- `ip addr show`
- `route`
- `cat /var/lib/dhcp/dhclient.leases`
- `cat /etc/resolv.conf`
- `curl ipinfo.io`
- `iptables -L`
- `nmap -p <IP_or_hostname>`
- `tcpdump -i <networkinterface> -n host <IP_or_hostname>`

## Part 2 - Network Info

### Network Info for <Your OS Here>

1. Hostname of the device:
2. MAC address of the NIC connected to the network:
3. IPv4 address:
4. Subnet mask:
5. Gateway address:
6. DHCP server address:
7. DNS server address:
8. Public IPv4 address:

### Network Info for AWS Instance

1. Hostname of the device:
2. MAC address of the NIC connected to the network:
3. IPv4 address:
4. Subnet mask:
5. Gateway address:
6. DHCP server address:
7. DNS server address:
8. Public IPv4 address:

## Part 3 - Subnet Translation

Translate the below CIDR notation subnets to their IP ranges:
1. `130.108.0.0/16`
2. `192.168.1.0/8`
3. `8.8.8.8/32`

Translate the below IP ranges to their CIDR notation subnets:
1. `192.168.1.0 - 192.168.1.255`
2. `172.16.0.0 - 172.16.255.255`
3. `132.189.13.78 - 132.189.13.78`

## Part 4 - Security

Screenshot of your changed Inbound Security Group rules.  
![Inbound Rules for Lab 10](relative/path/to/image)

Why should HTTP allow any IP, while SSH has restrictions?

## Extra Credit - Tattle Tale

### IPv4 Source Report

| Rank  | IPv4 Address | # of Attempts |
| ----- | ------------ | ------------- |
| 1     |              |     |
| 2     |              |     |
| 3     |              |     |
| 4     |              |     |
| 5     |              |     |

Commands to parse `csv` for report:

### Username Used Report

| Rank  | Username     | # of Attempts |
| ----- | ------------ | ------------- |
| 1     |              |     |
| 2     |              |     |
| 3     |              |     |
| 4     |              |     |
| 5     |              |     |

Commands to parse `csv` for report:
