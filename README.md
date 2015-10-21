Debian rules for librabbitmq 0.5.0
===

* debian/ contains debian rules
* GET is a script for getting and prepare building deb package

## Usage

```bash
$ ./GET
$ debuild -S -sa
$ dput ppa:<LP username:pparepository name> librabbitmq_0.5.0-ppa<revision>_source.changes
```
