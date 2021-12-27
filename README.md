user: ubuntu
pwd: windows equivalent for Fenyhozok

ubuntu installation to the sdcard
ssh login default: ubuntu:ubuntu
change password
update software

DHCP reserve IP address for MAC: 192.168.0.3
Port forwarding: 22
ssh-copy-id
ssh alias for pi
Followed microk8s guide: https://ubuntu.com/tutorials/how-to-kubernetes-cluster-on-raspberry-pi#4-installing-microk8s

Plan:
  - 🥇Have a Photo backup service
    - Auto mount external HDD (after plugin, after reboot)
    - Deploy Piwigo: https://piwigo.org/guides/install/manual
      - requires php and sql
      - Maybe useful: https://github.com/linuxserver/docker-piwigo
  - 🥈Have a minimal media player setup
    - Deploy transmission
    - Deploy minidlna
  - 🥉Have a cold backup in the cloud - updated per quarter year
  - Have a great media player setup
    - Deploy Kodi: https://github.com/ehough/docker-kodi
    - Or Stremio: https://github.com/sleeyax/stremio-streaming-server, https://github.com/Stremio/stremio-shell
  - Maybe play with a browser based IDE:
    - https://github.com/gitpod-io/openvscode-server
