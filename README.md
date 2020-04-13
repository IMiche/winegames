Winegames

A simple script for launching games through wine or proton with custom settings

## Getting Started

### Installation

Download the file (I suggest moving the file to /usr/local/bin/)

Create a new 'winegames' folder in your home directory and move all your applications here that you want to run later.

### Usage

Custom configurations for all your applications are saved in ~/.config/winegames.cfg

To add a new entry
```
winegames add [title] [32/64] [proton/wine] [pathToExe starting from ~/winegames/] [exeTitle] [custom prefix] [optional commands] [application params]
```
To launch an existing entry run
```
winegames start [title]
```
For a more detailed explanation and more commands run
```
winegames help
```
