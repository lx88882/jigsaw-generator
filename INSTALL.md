### Installing the software

If you are using a Debian or Ubuntu system, you should be able to
install this software using a command such as:

```
apt install jigsaw-generator
```

which will also install all prerequisites, and you need read no
further.

To install this software on other Linux or macOS systems, run the
three commands:

```
./configure
make
sudo make install
```

More configuration options can be found by running `./configure --help`

This software installs a number of supporting data files, and the
locations of these can be controlled using configuration options.

To uninstall this software, run

```
sudo make uninstall
```

You will need to have Python 3.x and a TeX distribution installed in
order to use this software.  You will also need the PyYAML module.
The latter can be installed with the command

```
sudo -H pip3 install PyYAML
```
