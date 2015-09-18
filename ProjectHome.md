This tool has three purposes :


1. SQL injection :

a)Error based: it scans for vulnerable websites based on common SQL errors for variety of databases.

b)Difference (true/false) scan: it scans for sites that do not display SQL errors but yet are vulnerable , the concept behind this scan is true / false query to the database which will give different answers which will then be scanned and in case of difference in length and content site will be considered vulnerable.


2.XSS scanner : it encrypts XSS vector and tries to scan result from web server , if XSS vector is found inside source than site is vulnerable. It only uses GET request to web server. NOTE: It will scan for XSS vector but it will not test if alert or any other event really happened.


3. Admin scanner : it scans for admin login locations , based on default list or any other that you have supplied.Response code 200 and 306 is considered success.


4. Shared hosting scanner : it send request to sameip.org and then parses html for pages

Thats is all hope you like it , please watch this video before using:
http://www.youtube.com/watch?v=TvYq9qS_85E
and visit the site http://www.maxone-tech.net for updates on this tool development.
If you want to say thanks or are interested to send me a dollar or euro , email me on maxonebt4@gmail.com

Virus scane : <b><a href='http://r.virscan.org/report/09e27e22e2a96172e9a2e524f46ab373.html'>http://r.virscan.org/report/09e27e22e2a96172e9a2e524f46ab373.html</a></b>