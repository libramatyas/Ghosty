## Compiling

**Note:** _Do NOT download or compile as the root user._

#### Download the dependencies required to build Kali:

If you are having problems compiling make sure you've got the latest version of `g++`.

==================

__Ubuntu-Based / Debian:__
```bash
sudo apt install g++ git
```
__Arch:__
```bash
sudo pacman -S base-devel git
```
__Fedora:__
```bash
sudo dnf install gcc-c++ git
```

===================

#### Downloading Ghosty:

```bash
git clone --recursive https://github.com/libramatyas/Ghosty
```

```bash
cd Ghosty
```

===================

#### Compile with script

You can build easily with script preincluded in Ghosty
```bash
./Ghosty -b
```


## Running

**Make sure Minecraft is running before injecting, or running the compiled app!**

Navigate to the directory where Kali was built if you have not ready.
```bash
cd Ghosty
```

Now, you can inject the hack with the Kali script
```bash
./Ghosty
```
or 
```bash
./Ghosty -r
```

You might be prompted to enter in your password, this is because the injection script requires root access.

*Note:* if you are crashing, please check if you are using the right minecraft client (forge, optifine, vanilla, etc.) for specific cheat client


## Credits
Special thanks to ArnoldasMK from which i stole this readme file :) [https://github.com/ArnoldasMK](https://github.com/ArnoldasMK)

