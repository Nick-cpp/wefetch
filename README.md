compilation from source code:

step 1:
you need installed gcc and git package ( Gnu Complier Collection )
```
$ sudo apt install gcc git - debian-based

$ sudo pacman -S gcc git - arch-based
```
step 2:
download the project repository
```
$ git clone https://github.com/Nick-cpp/wefetch
```
step 3:
compilation & installation

```
$ cd wefetch/

$ gcc wefetch.c -o wefetch

$ sudo mv wefetch /usr/bin/wefetch
```
step 4:
install default logos
```
$ mkdir -p ~/.config/wefetch/logos/

$ cp logos/* ~/.config/wefetch/logos/
```
step 5:
program launch
```
$ wefetch
```
Add your logos to ~/.config/wefetch/logos/

Confingure display distro via ~/.config/wefetch/wefetch.conf


<img width="539" height="472" alt="image" src="https://github.com/user-attachments/assets/f6fa2618-0aa6-4a72-a056-00bae02fa4ca" />


<img width="538" height="474" alt="image" src="https://github.com/user-attachments/assets/fb8b8830-3ca2-4a82-92ed-b57744793fb6" />
