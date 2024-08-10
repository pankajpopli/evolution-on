## Use the following commands to install evolution-on

```
sudo apt-get install -y libgconf2-dev intltool evolution-dev libecal1.2-dev libebook1.2-dev
autoreconf -sivf
./configure
make
sudo make install
sudo apt-get purge -y libgconf2-dev intltool evolution-dev libecal1.2-dev libebook1.2-dev
```
