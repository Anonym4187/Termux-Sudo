# Termux-Sudo 

sudo-termux
apt install git

git clone https://gitlab.com/st42/termux-sudo

cd termux-sudo

pkg install ncurses-utils

cat sudo > /data/data/com.termux/files/usr/bin/sudo

chmod 700 /data/data/com.termux/files/usr/bin/sudo

1. Clone termux-sudo or download to phone and extract
2. Open Termux
3. Install a dependency needed for sudo:
   ```pkg install ncurses-utils```
4. Change to cloned or extraction directory
5. Execute the following commands to place sudo into the correct directory with the proper permissions and ownership
