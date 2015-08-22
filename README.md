#Install speedtest-cli on Linux

cli-speedtest is a simple CLI client written in Python for measuring bidirectional Internet bandwidth by using Speedtest.net infrastructure. It works with Python 2.4-3.4. Installing the latest cli-speedtest is nothing more than downloading the Python script.

````
$ wget https://raw.githubusercontent.com/PC-Hawk/cli-speedtest/master/speedtest.py
$ chmod a+rx speedtest.py
$ sudo mv speedtest.py /usr/local/bin/speedtest
$ sudo chown root:root /usr/local/bin/speedtest
````

#Test Internet Connection Speed with speedtest-cli

It is straightforward to check your Internet speed with cli-speedtest. Running cli-speedtest command without any argument gets its job done.
````
$ speedtest
Retrieving speedtest.net configuration...
Retrieving speedtest.net server list...
Testing from Sample Provider (123.123.456.456)...
Selecting best server based on latency...
Hosted by Sample Host (San Francisco, CA) [0.10 km]: 24.546 ms 
Testing download speed........................................                       
Download: 953.92 Mbit/s
Testing upload speed..................................................
Upload: 733.01 Mbit/s   
````
