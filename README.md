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

$ gcc wefetch.c -o wefetch

$ sudo install -Dm755 wefetch /usr/bin/wefetch

step 4:
install default logos

$ mkdir -p ~/.config/wefetch/logos/

$ cp logos/* ~/.config/wefetch/logos/

step 5:
program launch

$ wefetch

Add your logos to ~/.config/wefetch/logos/

Confingure display distro via ~/.config/wefetch/wefetch.conf


<img width="544" height="474" alt="image" src="https://github.com/user-attachments/assets/442ac062-c477-4f30-a7af-38d2f5735f9b" />


<img width="558" height="483" alt="image" src="https://github.com/user-attachments/assets/c98718c8-1882-4ae9-8aab-a5ffbd66dbd4" />

