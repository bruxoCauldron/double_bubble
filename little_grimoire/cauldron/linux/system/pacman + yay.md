---
tags:
  - linux
  - system-admin
  - package-management
  - arch
---
##### resources: 

##### files:

### maintenance procedures
**update**:
run: `sudo pacman -Syu`

### installing from the arch pkg library
1. find name of package
2. run: `sudo pacman -S install <pkg name>`

### installing pkgs `from AUR
1. locate package in AUR and find the git url at the top of the package page
2. run: `git clone <url>`
3. `cd` into the directory it builds in `~/
4. run: `makepkg -sirc`
	^^^ `-sirc` handles dependencies, cleanup of build files, and also installs the package
5. follow instructions (psswrd, confirm install)
### uninstalling pkgs
run: `sudo pacman -Runs <package>`
`-R` = remove
`-u` = avoid removing packages if others depend on it
`-n` = no save, when it's gone it's really gone
`-s` = remove dependencies

AAAAC3NzaC1lZDI1NTE5AAAAIAHt05oBXi+FPu129OM3H3H8FaiIBlu+GlN1FXxyTseo