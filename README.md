# hamlib_rtl_server
This Repository will have all the code to controle the rtl_dongle from hamlib.<br>
The purpose of this project is to build a capability for hamlib to controle the RTL Dongle.<br>
![Alt text](rtl_dongle_hamlib_server.jpg?raw=true "Block diagram")<br>
# Project Status
This project just started.
Usage<br>
Start server<br>
python hamlibserver.py& <br>
Start hamlib rigctl<br>
rigctl -m 2 -r localhost:4575<br>
# How dose it work
rigctl will connect to python script hamlibserver.py witch will impliment the rtl-sdr interface to rtl_fm to controle frequensy and mode for the TCP stream by using the rtl_mux utility.<br>
So now you would be able to use GPREICT satelite tracking software to controle your SDR dongle (rtl dongle)<br>
# Related repositories
http://www.hamlib.org -- project Wiki, including list of supported rigs.<br>
http://sourceforge.net/projects/hamlib/ -- SourceForge.net project page.<br>
http://hamlib.git.sourceforge.net/git/gitweb-index.cgi -- Git repository via Web.<br>
http://hamlib.svn.sourceforge.net/viewvc/hamlib/ -- SVN repository via Web.<br>
