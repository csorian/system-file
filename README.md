# system-files
System-wide data and configuration files.

## uk-esc.map
Console keymap file with Caps Lock remapped to Escape.  Place in 
/usr/local/share/kbd/keymaps/ and set 
LANG=/usr/local/share/kbd/keymaps/uk-esc.map (usually in /etc/vconsole.conf).

## 00-keyboard.conf
X11 keyboard configuration with Caps Lock remapped to Escape, Euro sign on
AltGr+4 and Ctrl+Alt+Backspace.  Place in /etc/X11/xorg.conf.d/.

## motd
Message of the Day file containing notification of system-wide keyboard
remaps.  Place in /etc/ to display after users log in.

