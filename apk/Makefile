clean:


install:
	mkdir -p $(DESTDIR)/usr/bin
	cp apt-dater-host $(DESTDIR)/usr/bin

	mkdir -p $(DESTDIR)/etc/sudoers.d
	cp scripts/apt-dater-host $(DESTDIR)/etc/sudoers.d/
	chmod 0440 $(DESTDIR)/etc/sudoers.d/apt-dater-host
