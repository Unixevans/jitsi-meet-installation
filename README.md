# JITSI MEET INSTALLATION


## Development Environment
- `Debian Linux`
- `OpenJDK Java`
- `Apache2 Web Server`

## How To Installation
First Step update:
- `sudo apt update && sudo apt upgrade`
- `sudo apt install openjdk-11-jre-headless`
  
Add the repository Jitsi Bash
- `echo 'deb https://download.jitsi.org stable/' | tee /etc/apt/sources.list.d/jitsi-stable.list`
- `wget -qO - https://download.jitsi.org/jitsi-key.gpg.key | apt-key add -`
- `sudo apt update`

Install Jitsi Meet
- `sudo apt install jitsi-meet`
