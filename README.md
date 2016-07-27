# 76_SMAInverter.pm
FHEM Support for SMA Inverters

Copyright notice<br>
Published according Creative Commons : Attribution-NonCommercial-ShareAlike 3.0 Unported (CC BY-NC-SA 3.0)<br>
Details: https://creativecommons.org/licenses/by-nc-sa/3.0/

<br>

Credits:
- based on 77_SMASTP.pm by Volker Kettenbach with following credits:
- based on an Idea by SpenZerX and HDO
- Waldmensch for various improvements
- sbfspot (https://sbfspot.codeplex.com/)

<p>

Rewritten by Thomas Schödl (sct14675) with inputs from Volker, Waldmensch and DS_starter

Description:<br>
This is an FHEM-Module for SMA Inverters. <br>
Tested on Sunny Tripower 6000TL-20 and Sunny Island 4.4

Install in FHEM:<br>
Copy module 76_SMAInverter.pm in FHEM directory (e.g. /opt/fhem/FHEM )<br>
type in FHEM command: reload 76_SMAInverter.pm<br>
type in FHEM command: define (name) SMAInverter (passcode) (IP of inverter)<br>
example:<br>
define MySTP SMAInverter 0000 192.168.178.101<br>


Requirements:
This module requires:
- Perl Module: IO::Socket::INET
- Perl Module: Datime
