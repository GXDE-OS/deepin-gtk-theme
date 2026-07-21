![HEADER](./docs/img/header.png)

This package provides Deepin/GXDE themes for GTK 2, GTK 3 and GTK 4.

## Building
`./build-deb` is a build script that auto builds this package for Debian-based distros.

First you will need to give the premissions: 
```bash
$ chmod a+x ./build-deb
```

Then you may start to build the package:
```bash
$ ./build-deb -d
```

The artifacts may be found on the parent folder of project root.

After you're done just run this to clean up:
```bash
$ ./build-deb -c
```

Note that this also cleans artifact.


## License

This project is licensed under [GPLv3](LICENSE) or any later version.
