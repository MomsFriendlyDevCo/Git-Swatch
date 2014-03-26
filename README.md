Git-Swatch
==========
Git addon to link Git with SiteCopy to automate uploading to FTP servers.

The Script will repeatedly try to pull from remote, if its successful SiteCopy will be invoked to sync to a remote FTP server.


Installation
============
Run the following to install:

	git clone git@github.com:MomsFriendlyDevCo/Git-Swatch.git
	cd Git-Swatch
	sudo make install

Invoke with `git swatch <sitecopy-profile>`

For best results start the script inside a screen (e.g. `screen -dmS git swatch mySite`) to keep it running forever in the background.
