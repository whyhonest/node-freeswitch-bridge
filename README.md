# LDAP <> Freeswitch user bridge in NodeJS #

This is a bridge for integrating LDAP users into FreeSwitch. Unlike realtime Asterisk, it does not require many additional schemas to your directory, at the time only three fields are needed for sip password, vm password and mobile phone number. Extensions are based on uid numbers.

## Dependencies ##

<pre>
	npm install node-expat colors
	git submodule init
</pre>

Every original work included is licenced under Creative Commons BY-SH-NC
