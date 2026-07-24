[[Linux to do]]
[[obsidian to do]]

pacman upgrade update cleanup etc
### aesthetics
- [x] [[kitty]]
	- [x] maple mono nerd font
	- [x] colors uwu
	- [x] zsh + PowerLevel10k
		- [x] colored typing syntax
		- [x] better status/info bars
- [x] [[yazi]]
	- [x] colors
	- [x] ratio
	- [x] better searching (fzf?)
	- [x] QOL upgrades generally
- [x] [[hyprland|set wallpaper]]
	- [x] accidentally fubar'd the autostart section of hyprland.lua
- [ ] **~/Miku** ???
	- [x] cursor
	- [ ] miku in my terminal???
- [x] settle on a file browser
- [x] figure out how to set hyprland to dark mode default
	- [x] something to do with *gtk* ([[gtk + qt]])
### QoL
- [ ] set up [[neovim]] probably
	- [x] run `nvim` and in nvim run :`che` to run a health check. solve errors listed there have fun :)
	- [x] remove mention of nvim-jdtl or whatever
- [ ] figure out how to commit files to the [[GitHub|git repo]]
	- [ ] solve --set-upstream error when you go to push
- [x] set up brightness keys properly ..>n<..
- [x] hook up [[yazi]] so text files open in nvim
- [x] set up *bluetooth*
- [ ] figure out some kind of widget or bar situation
- [ ] figure out how to set zen as default browser (setting `local browser = "zen-browser"` in `~/.config/hypr/hyprland.lua` did not do the trick)
### security
- [x] AdGuard DNS
	- [x] `nmcli` shows two DNS connected, one of them *wireguard* located in `~/.config/pvpn/config.toml` 
- [x] [[Proton VPN]]
	- [x] opens in terminal [bruxo@cauldron ~]$ `pvpn` but does not connect
	- [x] TUI says `connecting...` but `pvpnctl status` says `conncted`

### misc
- [x] (without going down a rabbit hole) see what's current in the world of [[obsidian]]
- [x] get a TUI activity monitor
- [ ] [get rid](https://www.reddit.com/r/archlinux/comments/ki9hmm/how_to_properly_removeuninstall_packagesapps_with/) of anything you dont need
	- [x] generally just get down all the basics of using `pacman`
### config files to comb through
- [ ] `~/.zshrc`
- [ ] `~/.bashrc`
- [ ] `~/.config`
	- [ ] `/hypr`
		- [ ] `/hyprland.lua`
		- [ ] `hyprpaper.conf`
	- [ ] `/kitty`
		- [ ] `/current-theme.conf`
		- [ ] `/kitty.conf`
	- [ ] `/yazi`
		- [ ] `/package.toml`
		- [ ] `/them.toml`
		- [ ] `/yazi.toml`
- [ ] `~/p10k.zsh` idk if you even need this one because you aslo have p10k configured through ohmyzsh. idk if I need ohmyzsh