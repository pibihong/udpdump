udpdump
=======

a tcpdump version which support for python script plugins



Usage
----------------------------
run the python scirpt set by <b>$UDPDUMP_SCRIPT</b>, if $UDPDUMP_SCRIPT is not set use the udpdump.py in current directory


Interface
----------------------------

### support interface
		
		def welcome()
		
		def proc_udp(buf)


