# Pterodactyl Panel Installer
Installing & Upgrading Pterodactyl:
1. Unzip the scripts
2. Upload install.sh to your root directory (/root)
3. Log into SSH as root and do
Code:
chmod u+x install.sh
Code:
./install.sh
4. Answer the prompted questions

# Run After Installation
1. cd /srv/daemon
2. Paste the generated command from the panel
3. service wings restart
