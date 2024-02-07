# microsoft_edge_points_miner
Mines microsoft edge rewards points


Made from python.
The program will open a new window in microsoft edge. It will then go to bing.com. You should be automatically logged into your microsoft account after a few seconds. If you are not, then click sign in when prompted. You will only earn points if signed in.


The program will search the numbers 0-33 (34 search terms). As of when I wrote this, the maximum number of points allowed per day from searching (on desktop) is 170, with each search giving you 5 points.


There is also an .exe file you can run. If you want to build the .exe from source you can run:
```
pip install pyinstaller
pyinstaller --onefile -w ./msepoints.py
```

If microsoft questions your large amount of points, it wasn't me


Have fun