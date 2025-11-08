if you use arch by the way you can install it from AUR ( yay -S wefetch )

compilation from source code:

step 1:
you need installed gcc and git package ( Gnu Complier Collection )

$ sudo apt install gcc git - debian-based

$ sudo pacman -S gcc git - arch-based

step 2:
download the project repository

$ git clone https://github.com/Nick-cpp/wefetch

step 3:
compilation & installation


$ cd wefetch/

$ g++ -std=c++17 wefetch.cpp -o wefetch

$ sudo install -Dm755 wefetch /usr/bin/wefetch

step 4:
program launch

$ wefetch
