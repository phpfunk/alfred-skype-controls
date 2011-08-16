Skype Controls for Alfred
============

An AppleScript so you can call and send SMS via Skype from [Alfred App](http://alfredapp.com/). You can also start and quit Skype and manage your call forwarding settings as well as return your friend list. You will need Alfred and the Powerpack to use this.

Installation
----------------

To install Skype Controls in Alfred double click on the extension file: Skype Controls.alfredextension

How to use
----------------

Once installed with Alfred you can run the following commands

	skype start													::	Start skype (or you can use init)
	skype quit													::	Quit skype (or you can use kill, exit or end)
    skype call USER 											::  Make a call to a skype user
    skype call NUMBER 											::  Make a call to a telephone number
    skype call SPEED DIAL  										::  Make a call using a number on speed dial
    skype sms NUMBER MESSAGE									::  Send a text message to the number specified
	skype get cf												::	Growl notification of your call forwarding settings
	skype get cf to vm											::	Growl notification of your call forwarding voicemail settings
	skype get cf rules											::	Growl notification of your call forwarding rules
	skype get friends											::	Growl notification of your friend list (also automatically copies to clipboard)
	skype set cf (on|off)										::	Toggle your call forwarding setting
	skype set cf to vm (on|off)									::	Toggle your call forwarding to voicemail setting
	skype set cf timeout (seconds)								::	Set the timeout for skype calls before they are pushed to your forwarding option
	skype set cf rules ([[username|phone][,username|phone]])	:: Set a comma delimited list of usernames and numbers to use for forwarding
      

Examples
----------------
	$ skype start
	$ skype quit
	$ skype call phpfunk
    $ skype call +14845551212
    $ skype call 1
    $ skype sms +14845551212 Hey I am sending a text from Skype via Alfred!
	$ skype get cf
	$ skype get cf to vm
	$ skype get cf rules
	$ skype get friends
	$ skype set cf on
	$ skype set cf to vm off
	$ skype set cf timeout 10
	$ skype set cf rules phpfunk, +14845551212


Download
----------------
[Skype Controls](http://dl.dropbox.com/u/45930/Alfred%20Apps/Skype%20Controls/Skype%20Controls.alfredextension)
    

## Version History ##
### 1.1.0 - August 16, 2011###
 
- For SMS you no longer need the country code if number if U.S.
- Added support to start skype
- Added support to quit skype
- Added support to get your call forwarding settings and rules
- Added support to get your friend list
- Added support to set your call forwarding settings and rules

### 1.0.0 - August 15, 2011###
 
- Commit: Initial Release