kitty-arduino
=============

Code to run on kitty's arduino.

Depends on [CMPS10](https://github.com/kragniz/CMPS10) to interact with the
compass.

```bash
$ git clone https://github.com/abersailbot/kitty-arduino.git
$ cd kitty-arduino
$ git submodule init
$ git submodule update
```

Now, if ino tool is installed correctly (if you're using
[kitty-provisioner](https://github.com/abersailbot/kitty-provisioner) this is
done for you), you can compile with:

```bash
$ ino build
$ ino upload
```

Alternately, use make:

```bash
$ make install
```
