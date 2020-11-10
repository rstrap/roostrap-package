```
FILE=/data/data.com.termux/files/usr/.rstrap
if test -f "$FILE"; then
    echo "$FILE exists meaning rootstrap is installed..."
else
    echo install rootstrap from https://github.com/rstrap/rootstrap/
    FILE2=/data/data.com.termux/files/rootstrap/.rstrap_direc
    if test -f "$FILE2"; then
      Rootstrap directories is installed proceeding...
      # start install script here:
    else
      install for legacy devices at https://github.com/rstrap/rootstrap/
      
fi
```
