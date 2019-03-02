# Pterodactyl Panel Installer
<br>
# Installing & Upgrading Pterodactyl<br>
1.Run "cd .."<br>
2.Run "cd home"<br>
3.Run "git clone https://github.com/AdhityaRimba/Pter.git"<br>
4.Run "cd Pter"<br>
5.Run "chmod u+x install.sh"<br>
6.Run "./install.sh"<br>
7.Answer the prompted questions<br>
<br><br>
# Run After Installation
1.Reopen Your VNC/Putty<br>
2.Type "cd /srv/daemon"<br>
3.Run "npm install -g forever"<br>
4.Run "forever start src/index.js"<br>
(To stop the daemon use "forever stop src/index.js")<br>
5.Run "service wings restart"<br>
