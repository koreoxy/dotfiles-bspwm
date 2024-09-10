![2](https://github.com/user-attachments/assets/6bd1d6a6-27d0-4986-8a21-c76078e24de6)

Source Background Image : https://www.artstation.com/artwork/aYx4W0

# My Colors Theme
<table>
<tr>
    <th>Preview</th>
    <th>Variable</th>
    <th>Hex</th>
    <th>RGB</th>
</tr>
<tr>
    <td><img src="https://raw.githubusercontent.com/koreoxy/dotfiles-bspwm/main/assets/background.png"></td>
    <td><code>Background</code></td>
    <td><code>#141b1e</code></td>
    <td><code>rgb(20, 27, 30)</code></td>
</tr>
<tr>
    <td><img src="https://raw.githubusercontent.com/koreoxy/dotfiles-bspwm/main/assets/secondary-background.png"></td>
    <td><code>Secondary Background</code></td>
    <td><code>#0E111A</code></td>
    <td><code>rgb(14, 17, 26)</code></td>
</tr>
<tr>
    <td><img src="https://raw.githubusercontent.com/koreoxy/dotfiles-bspwm/main/assets/dark-gray.png"></td>
    <td><code>Dark Gray</code></td>
    <td><code>#6C695E</code></td>
    <td><code>rgb(108, 105, 94)</code></td>
<tr>
<tr>
    <td><img src="https://raw.githubusercontent.com/koreoxy/dotfiles-bspwm/main/assets/red-pink.png"></td>
    <td><code>Red Pink</code></td>
    <td><code>#C65D5A</code></td>
    <td><code>rgb(198, 93, 90)</code></td>
</tr>
<tr>
    <td><img src="https://raw.githubusercontent.com/koreoxy/dotfiles-bspwm/main/assets/green.png"></td>
    <td><code>Green</code></td>
    <td><code>#6f9170</code></td>
    <td><code>rgb(111, 145, 112)</code></td>
</tr>
<tr>
    <td><img src="https://raw.githubusercontent.com/koreoxy/dotfiles-bspwm/main/assets/orange.png"></td>
    <td><code>Orange</code></td>
    <td><code>#DD9546</code></td>
    <td><code>rgb(221, 149, 70)</code></td>
</tr>
<tr>
    <td><img src="https://raw.githubusercontent.com/koreoxy/dotfiles-bspwm/main/assets/light-gray.png"></td>
    <td><code>Light Gray</code></td>
    <td><code>#c8cbba</code></td>
    <td><code>rgb(200, 203, 186)</code></td>
</tr>
<tr>
    <td><img src="https://raw.githubusercontent.com/koreoxy/dotfiles-bspwm/main/assets/white-gray.png"></td>
    <td><code>White (gray)</code></td>
    <td><code>#cfcaca</code></td>
    <td><code>rgb(207, 202, 202)</code></td>
</tr>
</table>

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
