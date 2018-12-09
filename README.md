# Dracula for [st][]

A dark theme for [st][] based on the patch hosted by st's community at https://st.suckless.org/patches/dracula/.

![Screenshot][]

## Install

Clone st
```
git clone git://git.suckless.org/st
cd st
```
Apply the dracula patchfile
```
patch <<<"$(curl -s https://raw.githubusercontent.com/schlueter/dracula-for-st/master/dracula.diff)"
```
Build st
```
make
```
Run st
```
./st
```
Install st
```
sudo make install
```

## Team

Originally authored by:

Jesús López <jsus90@gmail.com>

This theme is maintained by the following person(s) and a bunch of [awesome contributors](https://github.com/schlueter/dracula-for-st/graphs/contributors).

[Brandon Schlueter][schlueter] <b@schlueter.blue>

## License

[GPLv3 License](./LICENSE)

[st]: https://st.suckless.org/
[Screenshot]: st-dracula.png
[schlueter]: https://github.com/schlueter/
