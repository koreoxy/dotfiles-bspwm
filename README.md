![VirtualBoxVM_MZpzV8SDZN](https://github.com/user-attachments/assets/750a79e8-fb96-4f5a-bf98-80c5e637fd7a)

Source Background Image : https://www.artstation.com/artwork/aYx4W0

## Install BSPWM

1. Update system and install package bspwm and sxhkd

```bash
sudo pacman -Syu
sudo pacman -S bspwm sxhkd
```

2. make directory config for bspwm and sxhkd

```bash
mkdir -p ~/.config/bspwm ~/.config/sxhkd
```

3. copy examples config

```bash
cp /usr/share/doc/bspwm/examples/bspwmrc ~/.config/bspwm/
cp /usr/share/doc/bspwm/examples/sxhkdrc ~/.config/sxhkd/
```

4. make file bspwmrc execute file

```bash
chmod +x ~/.config/bspwm/bspwmrc
```

5. run bspwm with startx in file .xinitrc

```bash
exec bspwm
```
