This repository contains some bootstrap autotools projects:

- [helloworld](./helloworld-glib) - helloworld c project
- [helloworld-glib](./helloworld-glib) - helloworld c project that uses glib
- [helloworld-check](./helloworld-check) - helloworld c project that uses [check](http://check.sourceforge.net/)

Basic steps for each project:

```bash
autoreconf -i
touch NEWS README AUTHORS ChangeLog
automake -a
./configure
make all
./src/helloworld
```
