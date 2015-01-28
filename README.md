# Twilio SMS-to-email service

This project is a small Ruby server that receives incoming SMS callbacks from Twilio and forwards the contents to a specified email address.

## Installation

* deploy it to a web server
* pass the MAIL_FROM and MAIL_TO environment variables to the script somehow (e.g. in server start scripts or nginx config, that depends on your configuration)
* set the incoming SMS URL in Twilio configuration to http://someserver/somepath/sms

## Credits

Created by [Kuba Suder](http://psionides.eu), licensed under WTFPL License.