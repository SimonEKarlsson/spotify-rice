```bash

yay -S spotify
yay -S spicetify-cli
sudo chmod 777 /opt/spotify -R
spicetify backup apply
sudo pacman -S pipewire pipewire-pulse pipewire-alsa wireplumber
systemctl --user daemon-reexec
systemctl --user enable --now pipewire pipewire-pulse wireplumber
```
