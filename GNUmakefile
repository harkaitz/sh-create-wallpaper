PROJECT=sh-create-wallpaper
VERSION=1.0.0
PREFIX=/usr/local
all:
clean:
install:

## -- BLOCK:license --
install: install-license
install-license: README.md LICENSE
	mkdir -p $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
	cp README.md LICENSE $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
## -- BLOCK:license --
## -- BLOCK:sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/create-wallpaper $(DESTDIR)$(PREFIX)/bin
	cp bin/ssh-h-wallpaper $(DESTDIR)$(PREFIX)/bin
	cp bin/ssh-h-profile $(DESTDIR)$(PREFIX)/bin
	cp bin/ssh-h-starticon $(DESTDIR)$(PREFIX)/bin
	cp bin/ssh-h-motd $(DESTDIR)$(PREFIX)/bin
## -- BLOCK:sh --
