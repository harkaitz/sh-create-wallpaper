PROJECT=sh-create-wallpaper
VERSION=1.0.0
PREFIX=/usr/local
all:
clean:
install:

## -- BLOCK:license --
install: install-license
install-license: 
	install -D -t $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT) LICENSE
## -- BLOCK:license --
## -- BLOCK:sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/create-wallpaper $(DESTDIR)$(PREFIX)/bin
	cp bin/ssh-h-wallpaper  $(DESTDIR)$(PREFIX)/bin
## -- BLOCK:sh --
