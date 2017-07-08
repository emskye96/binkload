# binkload

Loads a shared library into Counter-Strike: Global Offensive by replacing the seemingly unused `binkalnx64.asi` library.

## Usage

```
$ ./binkload
usage: ./binkload [input.so]

$ ./binkload /home/emma/test.so
OK
```

The specified library will then be loaded automatically when the game is next started.

The original `binkalnx64.asi` library can be restored by simply copying the file back to the `bin/linux64` folder.

```
$ cp binkalnx64.asi.backup ~/.steam/steam/steamapps/common/Counter-Strike\ Global\ Offensive/bin/linux64/binkalnx64.asi
```