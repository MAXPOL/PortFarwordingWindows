# PortFarwordingWindows

If you need forwording port on OS Windows
you can use part "3Proxy" server tcppm.
TCPPM - console port mapper.

For user "tcppm" you need download "tcppm.exe"
and ".bat" script:
#######start.bat######
#Start #NameAndPathProgramm #Key #PortLocalPC #IPAddressRemotePC #PortRemotePC
start tcppm.exe -d 80 10.0.0.1 80
#End

.bat files and programm will be in one folder.
Example tree resource:
C:/
  tcppm
    tcppm.exe
     start.bat

