ssh-proxy
============

You can use one of unit-files:
* [ssh](ssh-proxy0.service)
* [autossh](ssh-proxy1.service)

Just copy one of unit-files to `~/.config/systemd/user/`, change `<username>`,
do `systemctl --user daemon-reload` and `systemctl --user start ssh-proxy*`.

SOCKS should be on 9876 port. You can use it to get working Github or whatever.
