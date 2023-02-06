## iPerf3 parser and plotter.
Very budget implementation of reading the logfile produced by iPerf3 --logfile. Works for server and client.

Can't guarantee that this will work for special usages of different flags... This was implemented for a course at LTH.

### How to run
`python iperf3_parseplot.py <logfile.txt> <tcp OR udp>` 

Tcp or udp has to be specified since I didn't care to make the code automatically identify if the logfile being read is udp or tcp. The logfile has to be in the same directory as the iperf3_parseplot.py.

Do whatever you want with this.
