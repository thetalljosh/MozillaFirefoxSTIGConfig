# MozillaFirefoxSTIGConfig

This file will allow administrators to quickly STIG Mozilla Firefox (validated against Firefox 90.00). 

Settings in the firefox.txt file follow the format:
  lockpref("setting.name", value);
  
Use in an AD environment by distributing files via GPO computer configuration > preferences > files

There are 5 STIG vulnerabilities not included in this document, some of which can be set by GPO:

V-223179 - Can be set by GPO 
V-223169 - accepting risk in my environment, set as needed by Gpo
V-223156
V-223159
V-223151	


1) Unzip the file.

2) Place the autoconfig.js file in C:\<firefox path>\defaults\pref\ folder.

C:\Program Files\Mozilla Firefox\defaults\pref
C:\Program Files (x86)\Mozilla Firefox\defaults\pref

3) Place the firefox.cfg file in C:\<firefox path>\ folder.

C:\Program Files\Mozilla Firefox\
C:\Program Files (x86)\Mozilla Firefox\
