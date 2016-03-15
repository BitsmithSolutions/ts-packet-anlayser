# ts-packet-anlayser
Decode MPEG-2 transport streams
http://www.pjdaniel.org.uk/mpeg/

Usage:
```
	TSDECODE -i<input filepath> of TS file to decode
	         -p<search PID>
	         -q do not show progress when extracting
```
	Example: TSDECODE -ic:\test.mpg -p600
	will open file c:\test.mpg and process PID 600 packets


Automatically exported from code.google.com/p/ts-packet-anlayser
