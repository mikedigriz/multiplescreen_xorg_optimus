# multiplescreen_xorg_optimus
nvidia xorg for dell g3 15 (double screen intel+nvidia)
dont forget add 

blacklist nouveau
options nouveau modeset=0

lines to /etc/modprobe.d/disable-nouveau.conf

After update kernel u mast reinstall nvidia-driver!
Load recovery and then:
apt autoremove nvidia*
then launch ./nvidia-driver.run - downloaded driver
