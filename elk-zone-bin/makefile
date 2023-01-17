build:
	makepkg -sfi
clean:
	rm -rf src pkg Elk* elk*
get:
	makepkg -g
info:
	makepkg --printsrcinfo > .SRCINFO
release:
	cp ./PKGBUILD ./.SRCINFO ../../aur/elk-zone-bin
