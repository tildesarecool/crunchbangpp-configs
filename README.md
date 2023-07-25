# crunchbangpp-configs
Scripts and configuration files for setting up a cbpp-like config on other os like ubuntu server

I'm attempt a few things here:
## run linux on extremely old hardware (2009 or so atom and 2 gig ram)
## duplicate setup of debian-based crunchbang++ default xorg/openbox config as close as possible using ubuntu server 16.04LTS

This means I start with no X even. have to install everything from scratch. Boring to to Arch enthusiasts. For me it's kind of a see-if-I-can experiment.

I chose 16.04 hoping the system requirements would be that much lower. And 16.04 is the oldest one that utilizes systemd. A strange reason perhaps.

I think 16.04 server actually does come with git so the steps could probably be reduced further.

I assumed I would have to type this one thing in nothing else but perhaps not:

sudo apt-get update && sudo apt-get upgrade -y && sudo apt-get install git -y && mkdir ~/repos && cd ~/repos && git clone https://github.com/tildesarecool/crunchbangpp-configs.git

This at least I'm pretty sure I can't avoid typing in 

git clone https://github.com/tildesarecool/crunchbangpp-configs.git

for getting updates, it would be:

git pull https://github.com/tildesarecool/crunchbangpp-configs.git


And this is my package list so far:

sudo apt install xorg openbox tint2 obconf xcompmgr synaptic lxterminal yad vim tmux git network-manager screen lxappearance nitrogen xterm nemo pluma nano lxpolkit rofi -y

