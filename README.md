# linux_settings

### 1. set shift+numpad behave like windows
reference: https://askubuntu.com/a/57189

edit file /etc/default/keyboard
and set `XKBOPTIONS="numpad:microsoft"`

then `sudo dpkg-reconfigure keyboard-configuration` to make it work
