This is some Python code that I wrote to get monthly/yearly domain hits/usage from EZproxy logs. It counts the number of lines in the log per domain, per user, per second. Counting per second eliminates counting of excess lines in the log that were generated by one click and therefore makes the data more realistic. The code is based on the following log format which may be different depending on what you record in your logs and in what order: 
IP_address sessionID userID [19/Jun/2016:03:00:03 +1000] "GET https://www.url.com HTTP/1.1" 200 0
This equates to: IP address, session ID, user ID, date/time/timezone, HTTP method, url, HTTP status, bytes downloaded. 

To run this code, download Anaconda from https://www.continuum.io/downloads
Download the Python 3.5 version.
If you are asked during the installation process whether you�d like to make Anaconda your default Python installation, say yes.

Once it's installed, open Anaconda Navigator and launch the Jupyter notebook. This opens a browser tab which displays the file directories of your computer. Save the 'Ezproxy Analysis - domain count.ipynb' file to your computer and open it through the Jupyter notebook browser interface. It will open as another browser tab. 

To run the code, click in the first box of code then type Shift+Enter. In the top right corner you will see 'Python 3' with a circle next to it. If the circle is empty, then the code has finished running. If the circle if full (i.e. dark) then wait for the code to finish running before running the next box of code.

I have included step by step instructions in the .ipnb file itself.


