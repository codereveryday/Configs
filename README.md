# Configs
Things you might need the lua.rc is still begin worked on but i will update it to time to time 

color scripts https://gitlab.com/dwt1/shell-color-scripts

cava https://github.com/karlstav/cava

terminal clock https://github.com/xorg62/tty-clock

compton https://github.com/chjj/comp

cool themes for awesome https://github.com/lcpz/awesome-copycatston

https://pwmt.org/projects/zathura/
zathura a doc viewer if you want zathura transparent then you gotta patch the code in the zathura.rc

patch 
https://www.reddit.com/r/unixporn/comments/eq1714/i3_zathura_with_proper_transparency/

https://github.com/b4dtR1p/awesome/blob/master/.xinitrc
this code right here allows you to go into tty and boot up awesome while in your current de or wm 
make sure to paste this code in your .xintrc 

or paste this script here in your .xinitrc

/bin/sh
#
# ~/.xinitrc
#
# Executed by startx (run your window manager from here)

if [ -d /etc/X11/xinit/xinitrc.d ]; then
  for f in /etc/X11/xinit/xinitrc.d/*; do
    [ -x "$f" ] && . "$f"
  done
  unset f
fi

# exec enlightenment_start
# exec i3
# exec mate-session
# exec xmonad
# exec startlxqt
# exec startlxde
# exec awesome
# exec bspwm
# exec gnome-session
# exec gnome-session --session=gnome-classic
# exec startplasma-x11
# exec startplasma-wayland
# exec startxfce4
# exec startfluxbox
# exec openbox-session
# exec cinnamon-session
# exec pekwm
# exec catwm
# exec dwm
# exec startede
# exec icewm-session
# exec jwm
# exec monsterwm
# exec notion
# exec startdde       # deepin-session



vim cheat sheet :)
https://vim.rtorr.com

another cheat sheet 
https://github.com/chubin/cheat.sh 
or type cheat.sh in your browser 

cheat.sh
Has a simple curl/browser/editor interface.
Covers 56 programming languages, several DBMSes, and more than 1000 most important UNIX/Linux commands.
Provides access to the best community driven cheat sheets repositories in the world, on par with StackOverflow.
Available everywhere, no installation needed, but can be installed for offline usage.



how to have images in neofetch 
https://github.com/dylanaraps/neofetch/wiki/Images-in-the-terminal
