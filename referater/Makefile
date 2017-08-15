# pir-hordaland.git/referater/Makefile
# File ID: 4e849c5c-8188-11e7-8f48-f74d993421b0

default: referat.2017-06-29.pirhord-styret.html

referat.2017-06-29.pirhord-styret.html: referat.2017-06-29.pirhord-styret.mediawiki
	pandoc -f mediawiki -t html referat.2017-06-29.pirhord-styret.mediawiki >referat.2017-06-29.pirhord-styret.html

clean:
	rm -f referat.2017-06-29.pirhord-styret.html
