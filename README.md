# pyt-deb-installer

```sh
curl -O https://www.python.org/ftp/python/$PYT_VERSION/Python-$PYT_VERSION.tar.xz
tar -xf Python-$PYT_VERSION.tar.xz
cd Python-$PYT_VERSION
sudo make clean && ./configure --enable-optimizations --prefix=/opt/python/$PYT_VERSION --exec-prefix=/opt/python/$PYT_VERSION && make -j $JOBS && sudo make altinstall
```
