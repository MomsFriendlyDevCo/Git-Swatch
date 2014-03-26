Git-Swatch
==========
Git addon to link Git with SiteCopy.

The Script will repeatedly try to pull from remote, if its successful SiteCopy will be invoked to sync to a remote FTP server.


Installation
============
1. Install the `git-swatch` script somewhere in your `$PATH`.
2. Make sure you've defined a suitable site definition in `~/.sitecopyrc`.
3. Invoke with `git swatch <sitecopy-profile>`

For best results start the script inside a screen (e.g. `screen -dmS git swatch mySite`) to keep it running forever in the background.
