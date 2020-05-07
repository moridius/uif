# UIF

I work with different distributions and it's annoying for me that common tasks have a different syntax on every system:
- Search for a package (is it apt or pacman on this box?)
- Install updates
- Enable and start services (what was the syntax on Void Linux?)
- Reboot the system
- ...

UIF is a shell script, because shell runs everywhere (except for that rarely used OS from Redmond).

## Installation
```
git clone https://github.com/moridius/uif.git
cd uif
ln -s ./pkg ./srv
ln -s ./pkg ./sys
```
It's 3 in 1: Call `pkg` to handle your packages, `srv` to handle services and `sys` to do system tasks like a reboot.
