# My Config

My configuration is composed of multiple configuration files respectively to be used with these packages:

	- i3
	- Polybar
	- Terminator
	- Vim
	- Dunst
	- Redshift

## i3

i3 is a window manager, configure it to feel at home on your desktop

### Installation
	
	1. `sudo apt install i3`

### Configuration file 

	The configuration file is located at: ~/.config/i3/config

## Polybar

This is the tool I use for my taskbar.


### Installation

	Install it by following the instructions from this git repo: https://github.com/polybar/polybar

### Configuration file 

	The configuration files are located at: ~/.config/polybar

## Terminator

	Terminator is a highly customizable terminal. And it has a cool name.

### Installation

	1. `sudo apt install terminator`

### Configuration file 

	The configuration file is located at ~/.config/terminator/config

## Vim

	Vim - Vi IMproved is a terminal text editor

### Installation

	1. `sudo apt install vim`

### Configuration file 

	1. The configuration file is located at ~/.vimrc
	2. The colors folders containing the color themes is located at ~/.vim/colors/

## Dunst

	Dunst is a notifications manager, highly customizable.

### Installation

	1. Install these dependencies (for Ubuntu): `sudo apt install libdbus-1-dev libx11-dev libxinerama-dev libxrandr-dev libxss-dev libglib2.0-dev libpango1.0-dev libgtk2.0-dev libxdg-basedir-dev`
	2. Then Follow these steps:
		1. git clone https://github.com/dunst-project/dunst.git
		2. cd dunst
		3. make -j5
		4. sudo make install

	3. If you need further information, find it here: https://linuxconfig.org/get-better-notifications-in-your-wm-with-dunst

### Configuration file

	The configuration file is located at ~/.config/dunstrc
	
## Redshift
	
	Redshift is a blue light filter package.
	
### Installation 

	1. `sudo apt install redshift`
	
### Configuration

	No configuration is needed, but check the official documentation if you want to select your geographical zone manually for example.

## Rofi

	A replacement to Dmenu!

### Installation 
	
	1. `sudo apt install rofi`

### Configuration file

	The configuration file for rofi is located at /etc/rofi.conf

## Compton
	
	It is a composer. I use it for the transparency like everyone else.

### Installation

	1. `sudo apt install compton`

### Configuration file

	The configuration file is located at ~/.config/compton.conf

## BetterLockScreen

	Better version of i3lock & i3lock-color

### Installation

	Install i3lock & i3lock-color and all their dependencies.

### Configuration

	Configuration can be found in the package's Github.
