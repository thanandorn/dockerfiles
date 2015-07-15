Linux / OSX
===========

```
$ cd puppet
$ docker run --rm -v “$PWD”:/etc/puppet -w /etc/puppet thanandorn/librarian-puppet clean
$ docker run --rm -v “$PWD”:/etc/puppet -w /etc/puppet thanandorn/librarian-puppet install --verbose
```

Windows
=======

```
$ cd puppet
$ docker run --rm -v //c/Users/jon.snow/Documents/GitHub/Config/puppet:/etc/puppet -w //etc/puppet thanandorn/librarian-puppet clean
$ docker run --rm -v //c/Users/jon.snow/Documents/GitHub/Config/puppet:/etc/puppet -w //etc/puppet thanandorn/librarian-puppet install --verbose
```
