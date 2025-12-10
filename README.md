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


<img width="593" height="457" alt="image" src="https://github.com/user-attachments/assets/b6fa77d2-9174-40ee-9641-22fd09c7bc3e" />


<img width="595" height="468" alt="image" src="https://github.com/user-attachments/assets/de26bfed-b43c-45b7-ad09-ce1c88432f65" />
