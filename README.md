# rhost_daemon for Ubuntu
Installation instructions, such as they are

1) place rhost.service in /etc/systemd/system/
2) Make sure to change the values of User, WorkingDirectory, ExecStart and ExecStop to suit your system's needs
3) Make a folder in the game folder called system.d
4) copy start.sh and stop.sh there
5) sudo systemctl daemon-reload
6) sudo systemctl start rhost
7) ???
8) profit


