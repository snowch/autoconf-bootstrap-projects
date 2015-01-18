This repository contains some bootstrap autotools projects:

- [helloworld](./helloworld-glib) - helloworld c project
- [helloworld-glib](./helloworld-glib) - helloworld c project that uses glib

Basic steps for each project:

```bash
autoreconf -i
touch NEWS README AUTHORS ChangeLog
automake -a
make
make install
```
