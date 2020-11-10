# roostrap-package
rootstrap template package


first clone/fork and modify install.sh accordingly...

and create pull request

if it is a debian package please make the installer:
```
pkg install wget
or
lx4 install wget

wget <https://linktodeb.com>
```

If you have made the debian package and want it to be included in the official repository then fork rootstrap-repo and create a pull request after modifying

repo: https://github.com/rstrap/repo

after doing this and pull request is accepted:

to install your package:

rstrap -install --${package_name}

then...

automatically:

wget ${install-script} saved to /data/data/com.termux/files/rootstrap/install-scripts/

wget ${uninstall-script} saved to /data/data/com.termux/files/rootstrap/uninstall-scripts/

bash path to install script///

