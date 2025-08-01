# Configurações no Arch Linux
Minhas configurações ao instalar o Arch Linux.
1. sudo pacman -Syu
2. sudo nano /etc/pacman.conf
   * Descomentar a linha Color
   * Adicionar ILoveCandy
   * Habilitar ParallelDownloads(10)
4. sudo pacman -S git nano neofetch vlc gparted htop virtualbox kdeconnect okular gnome-system-monitor gufw fwupd
5. sudo pacman -S ffmpeg gst-plugins-ugly gst-plugins-good gst-plugins-base gst-plugins-bad gst-libav gstreamer
6. sudo pacman -S --needed git base-devel && git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si
7. sudo pacman -S flatpak
8. flatpak install flathub com.visualstudio.code com.discordapp.Discord com.github.unrud.VideoDownloader org.gnome.Calculator org.gnome.gitlab.dqpb.GMetronome org.gimp.GIMP org.audacityteam.Audacity com.obsproject.Studio
9. https://github.com/shiftkey/desktop
