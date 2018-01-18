# dominos

Dominos - board game of pygame.

Automatically exported from code.google.com/p/dominos

---  

## Build deb

Install bash-deb-build:

```
$ wget https://github.com/zvezdochiot/bash-deb-build/releases/download/0.3/bash-deb-build_0.3_all.deb
$ sudo dpkg -i bash-deb-build_0.3_all.deb
```

Get source Dominos:

```
$ git clone https://github.com/zvezdochiot/pygame-dominos
```

Make deb package:

```
$ cd pygame-dominos
$ cd deb
$ sudo bash-deb-build lzma
```

Install deb package:

```
$ sudo dpkg -i *.deb
```

2018  
---  
zvezdochiot
