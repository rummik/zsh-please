# ZSH Please
A polite way to have your computer do something as another user - usually root.

Installable with:
- [Zplug](https://github.com/zplug/zplug): `zplug "rummik/zsh-please"`
- [Antigen](https://github.com/zsh-users/antigen): `antigen bundle rummik/zsh-please`

Use it to:
- Reboot a system: `please reboot`
- Shutdown a system: `please shutdown now`
- Read a file: `please less /var/log/syslog`
- Change init level: `please init 1`
- Install grub: `please grub-install`
- Partition a disk: `please fdisk /dev/sdb`
- Check a disk: `please fsck -y /dev/sda2`
- Run an X instance: `please startx`
- Restart a service: `please systemctl restart network-manager.service`
- Install packages: `please apt install vim`
- Fix your install: `please pacman -Syu base`
- Become root: `please sudo su`
- Kill a process: `please killall -9 systemd`
- Clean up space: `please rm -rf /`
