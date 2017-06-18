# linux_settings

### 1. set shift+numpad behave like windows

edit file /etc/default/keyboard
and set `XKBOPTIONS="numpad:microsoft"`

then `sudo dpkg-reconfigure keyboard-configuration` to make it work
reference: https://askubuntu.com/a/57189
