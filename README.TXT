This is a demo using Long Beach, California's 2013 Flu Shot Clinics as listed at http://www.longbeach.gov/news/displaynews.asp?NewsID=6660&targetid=51.

[Much of the below is from tkompare's flushots2013. TODO: Update README. –Fureigh]

I have again partnered with the Chicago Department of Public Health (CDPH) to create an updated flu shot finder web application. Currently it has all the CDPH free locations and events. It also includes Walgreens, Dominick's, Jewel/Osco, and CVS locations that offer flu shots.

I created this as a volunteer effort. The code that runs it is open, completely free, and reusable by anyone.

Special thanks to Tom Kompare of Chicago, who created chicagoflushots (https://github.com/tkompare/flushots2013).

NOTES:

-- This a HTML/CSS/JavaScript web application. It does have one small PHP file to construct an iCal file for users who want a calendar reminder of one-off events. This PHP file should be simple enough to rewrite in whatever server-side language is available in your environment.

-- I used the generic Bootstrap 3 download, except it has one modified LESS variable: '@screen-sm' was set to '860px'.

-- If you want to reuse this code for your city/county/province/state, a good place to start is in main.js and altering the properties of the "Default" object at the top of the file.

-- I try to use meaningful variable names, so hopefully the code won't be too hard to follow.

-- The data behind this site is a Google Fusion Table and is found here: https://www.google.com/fusiontables/DataSource?docid=1n5PNdxLZu9-neTWzfpnpGknTv3rntZ99IMUPpiM
