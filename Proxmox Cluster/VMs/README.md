# Details
## VMID
ID Number for each virtual machine, assigned automatically upon creation.
## VM Types
**LXC** - Linux Container. Not fully virtualised, but allows easy segmentation for applications.
**VM** - Fully virtual computer.
# VM List

| VMID    | Type    | Hostname          | LAN IP             | Description                                                                     |
| ------- | ------- | ----------------- | ------------------ | ------------------------------------------------------------------------------- |
| 100     | VM      | amp-panel         | 192.168.101.19     | AMP Game Hosting Web Panel                                                      |
| 101     | LXC     | webhost           | 192.168.101.3      | Hosts various web applications                                                  |
| ~~102~~ | ~~LXC~~ | ~~bot-host~~      |                    | ~~Discord Bot Host~~                                                            |
| 102     | LXC     | ui-controller     | 192.168.99.200     | Ubiquiti Controller                                                             |
| 103     | LXC     | portainer         | 192.168.101.5      | Portainer Docker Control WebUI                                                  |
| 104     | LXC     | scraper           | 192.168.101.30     | Radar and Pastebin Scraper                                                      |
| 105     | VM      | amp-host          | 192.168.101.20     | AMP Game Hosting Compute Node                                                   |
| 106     | LXC     | monitoring        | 192.168.0.5        | Runs various Monitoring services                                                |
| ~~107~~ | ~~LXC~~ | ~~netbox~~        |                    | ~~Old IPAM software~~                                                           |
| 107     | LXC     | dashy             | 192.168.101.4      | Hosts Dashy Dashboard                                                           |
| ~~108~~ | ~~LXC~~ | ~~wazuh~~         | ~~192.168.101.50~~ | ~~Hosts Wazuh SIEM~~                                                            |
| 109     | LXC     | proxy             | 192.168.101.2      | Hosts a reverse-proxy for internal services                                     |
| 110     | LXC     | logging           | 192.168.101.250    | Hosts InfluxDB and MySQL for Logging                                            |
| 111     | LXC     | authentik         | 192.168.101.101    | Hosts Authentik Identity Provider                                               |
| ~~112~~ | ~~VM~~  | ~~checkmk~~       |                    | ~~CheckMK Monitoring host~~                                                     |
| 113     | LXC     | paperless-ngx     | 192.168.101.10     | Hosts Paperless-NGX Document Organiser                                          |
| ~~114~~ | ~~LXC~~ | ~~wireguard-old~~ |                    | ~~VPN Host~~                                                                    |
| 114     | VM      | pirateship        | 192.168.101.11     | Pirate Host, runs Jellyfin and QBittorrent via Mullvad VPN                      |
| ~~115~~ | ~~LXC~~ | ~~bingus~~        |                    | ~~Dakota's test machine~~                                                       |
| 116     | LXC     | adguard           | 192.168.200.1      | Adguard DNS Ad-Blocker                                                          |
| ~~117~~ | ~~VM~~  | ~~amp-host2~~     | ~~192.168.101.21~~ | ~~AMP Game Hosting Compute Node~~                                               |
| 118     | LXC     | mailcow           | 192.168.101.6      | Self Hosted Mail Server with Webmail                                            |
| 119     | LXC     | homeassistant     | 192.168.101.7      | Homeassistant OS, provides dashboard and automation stuff for IoT devices       |
| ~~120~~ | ~~LXC~~ | ~~actualbudget~~  |                    | ~~Budget Tracking software, not very good tbh~~                                 |
| 121     | LXC     | wireguard         | 192.168.102.100    | VPN Host                                                                        |
| 123     | LXC     | nextcloud         | 192.168.101.9      | Hosts Nextcloud, a Google Drive replacement, as well as a fileserver via docker |
| 124     | LXC     | photohost         | 192.168.101.8      | Hosts SOMETHING as a photo album / portfolio                                    |
| 125     | LXC     | dnd               | 192.168.101.12     | Runs stuff for PAG DND                                                          |
| 126     | VM      | win-amp           | 192.168.101.22     | Windows-Based AMP Compute Host                                                  |
| 127     | LXC     | gotify            | 192.168.101.13     | Hosts an open source notification platform                                      |
| 128     | LXC     | watchyourlan      | 192.168.101.31     | Local network scanner, detects new devices on the network                       |
| 129     | LXC     | n8n               | 192.168.101.14     | Automation Platform                                                             |
