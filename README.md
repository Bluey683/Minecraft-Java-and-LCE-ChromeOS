# Minecraft-Java-and-LCE-ChromeOS
Minecraft for ChromeOS. Using Prism Launcher and Legacy PC Edition

# How to Install

sudo dpkg --add-architecture i386
sudo apt update
sudo apt upgrade
sudo apt install -y mesa-vulkan-drivers mesa-vulkan-drivers:i386 libvulkan1 libvulkan1:i386 libglx-mesa0 libglx-mesa0:i386 mesa-utils mesa-utils:i386 mangohud libgl1-mesa-glx libgl1-mesa-glx:i386 libgl1-mesa-dri libgl1-mesa-dri:i386 libgl-dev git openjdk-25-jdk unzip flatpak

flatpak --user remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo

flatpak install flathub org.prismlauncher.PrismLauncher
flatpak run org.prismlauncher.PrismLauncher

mkdir .wine
cd .wine
mkdir games
cd games
mkdir lce
cd lce

Please Download LCE on Work!
wget https://github.com/XeraPlugins/minecraftlce-server/releases/download/1.0/LCEWindows64.zip
unzip LCEWindows64.zip

Open Lutris -> Minecraft.Client.exe

sudo rm LCEWindows64.zip

cd ..
cd ..
cd ..

sudo apt install steam steam-devices
Not Work!
wget https://cdn.fastly.steamstatic.com/client/installer/steam.deb
sudo apt install ./steam.deb

Thank You!
