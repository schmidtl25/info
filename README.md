### Installing from tarball
```
tar -xzf archive-name.tar.gz
cd archive-name
./configure
make
sudo make install
```

### Bash stuff
clear command cache (changing PATH or installing new stuff)  
`hash -r`

### tmux stuff
```
sudo dnf install libevent-devel
sudo dnf install ncurses-devel
```
download latest from https://github.com/tmux/tmux/wiki

```
cd <tmux download dir>
./configure
sudo make install
```

- copy-paste: https://www.seanh.cc/2020/12/27/copy-and-paste-in-tmux/

#### xsel
sudo dnf install https://download-ib01.fedoraproject.org/pub/epel/8/Everything/x86_64/Packages/x/xsel-1.2.0-26.el8.x86_64.rpm
