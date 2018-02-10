all:
	

install:
	@test -d $(DESTDIR)/opt || mkdir -p $(DESTDIR)/opt
	cp -r Postman $(DESTDIR)/opt/postman
	
	@test -d $(DESTDIR)/usr/bin || mkdir -p $(DESTDIR)/usr/bin
	cp postman $(DESTDIR)/usr/bin
	
	@test -d $(DESTDIR)/usr/share/applications || mkdir -p $(DESTDIR)/usr/share/applications
	cp Postman.desktop $(DESTDIR)/usr/share/applications
	
	@test -d $(DESTDIR)/usr/share/icons/hicolor/128x128/apps || mkdir -p $(DESTDIR)/usr/share/icons/hicolor/128x128/apps
	cp Postman/resources/app/assets/icon.png $(DESTDIR)/usr/share/icons/hicolor/128x128/apps/postman.png
