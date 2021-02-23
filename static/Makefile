all: copy  academicons fontawesome

copy:
	cp -r ../../static/* . 2>/dev/null | true

academicons-v1.8.6.zip:
	wget -q https://github.com/jpswalsh/academicons/archive/v1.8.6.zip -O academicons-v1.8.6.zip

academicons: academicons-v1.8.6.zip
	unzip -Dq academicons-v1.8.6.zip
	rm academicons-v1.8.6.zip
	mv academicons-1.8.6 academicons

fontawesome-free-5.15.2-web.zip:
	wget -q https://github.com/FortAwesome/Font-Awesome/releases/download/5.15.2/fontawesome-free-5.15.2-web.zip -O fontawesome-free-5.15.2-web.zip

fontawesome: fontawesome-free-5.15.2-web.zip
	unzip -Dq fontawesome-free-5.15.2-web.zip
	rm fontawesome-free-5.15.2-web.zip
	mv fontawesome-free-5.15.2-web fontawesome

