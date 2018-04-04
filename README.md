# Preparing Stage

## Guides

I am using ElementaryOS on a Mac guide to guide me on this process, since ElementaryOS is also based on Ubuntu distros
https://github.com/aroman/elementary-on-a-mac

*Also Gentoo's config for MBP 13" 2015 for drivers
https://github.com/coldnew/macbookpro-2015-config*

## MacOS prep

### Etcher USB Creator 
  
  I use Etcher to create a bootable linux thumbdrive.
  
### Ubuntu Linux ISO (Ubuntu-ISO variant)
  
  I choose Ubuntu_mini to install only package I needed to use the OS.
  
### MBP Partitioning

  I want 65% Linux and 35% MacOS
  
### rEFInd Installation
  
  Required for booting
  
#### rEFInd Theme (Optional)
  
  https://sdbinwiiexe.deviantart.com/art/rEFInd-Next-Theme-407754566
  
  
  
  # Temporary
  
  == Guide on Skipping unwanted APT Package ==
  
https://mike632t.wordpress.com/2014/02/05/configuring-apt/#locales


==THAI FONTS (For browser, GUI, etc.)==

xfonts-thai msttcorefonts

==Basic GUI==

xserver-xorg xserver-xorg-core xfonts-base xinit x11-xserver-utils

==PulseAudio==

gstreamer1.0-plugins-base gstreamer1.0-plugins-good gstreamer1.0-plugins-bad pulseaudio gstreamer1.0-pulseaudio pavucontrol

==Utilities==

htop
firefox

==Terminal==

lxterminal
!!No need if use desktop-environment-core package

==Login GUI==

lightdm lightdm-gtk-greeter

==DesktopEnvironment==

mate-desktop-environment-core <-- Pure MATE Package

==Thai Input==

==Power Management==

powertop
tlp

==Fan Control==

https://github.com/dgraziotin/mbpfan

==Modifier Keys==

https://elementaryos.stackexchange.com/questions/7889/use-macos-style-modifier-keys


  
  
  
