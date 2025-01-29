# repo
My debs repo
```sh
cat << EOF >> $PREFIX/etc/apt/sources.list.d/imobiledevice.list
deb [trusted=yes] https://xunmod.github.io/repo termux main
deb [trusted=yes] https://xunmod.github.io/repo termux root
EOF
pkg up
```
