Installing on MacOS The easiest way to install on MacOS is to use Homebrew. Just run the following in a terminal:

```
brew update
brew install glfw3 glew pkg-config
```

---

Installing on Ubuntu 16 The easiest way to install on Ubuntu is to use apt-get. Just run the following:

```
sudo apt-get update
sudo apt-get install pkgconf libglfw3 libglfw3-dev libglew1.13 libglew-dev
```

---

Installing on Ubuntu 18 The easiest way to install on Ubuntu is to use apt-get. Just run the following:

```
sudo apt-get update
sudo apt-get install pkgconf libglfw3 libglfw3-dev libglew2.0 libglew-dev
```

---

Installing on Arch Linux glew and glfw-x11 are available in Extra and Community, respectively. Ensure that these are enabled in your pacman.conf, then run:

```
sudo pacman -S pkgconf glew glfw-x11
```
