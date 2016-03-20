**Moshi Moshi** is a VoIP Bot written in Python that uses SIP as VoIP Protocol, Text-to-speech engines for Output, and DTMF Tones for Input.

It is part of a talk ("Sounds Like Botnet") given at DEF CON 19 and BSidesLV 2011 on VoIP Botnets by Itzik Kotler and Iftach (Ian) Amit.

Dependencies:

Core:

- Python 2.7+ (download from http://www.python.org)

- SIP SIMPLE Client (download from http://sipsimpleclient.com/)

Extras:

- catdoc (download from http://freshmeat.net/projects/catdoc/)

- Text-to-speech engine such as (but not limited to) http://sourceforge.net/projects/espeak/ , Mac OS X 'say' and etc.

Install:

Use 'sip-settings' to set your SIP settings and save it as 'config' in the same directory as 'moshimoshi.py'

Run ./moshimoshi.py with SIP conference call details (e.g. '300@1.2.3.4')

By default 'moshimoshi.py' assumes default SIP port, use ':' to change it (e.g. '300@1.2.3.4:31337')

For more details, please see README file