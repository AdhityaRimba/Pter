# Pterodactyl Panel Installer

# Installing & Upgrading Pterodactyl
1.Run "cd .."
2.Run "cd home"
3.Run "git clone https://github.com/AdhityaRimba/Pter.git"
4.Run "cd Pter"
5.Run "chmod u+x install.sh"
6.Run "./install.sh"
7.Answer the prompted questions

# Run After Installation
1.Reopen Your VNC/Putty
2.Type "cd /srv/daemon"
3.Run "npm install -g forever"
4.Run "forever start src/index.js"
(To stop the daemon use "forever stop src/index.js")
5.Run "service wings restart"
