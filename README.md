# Apache-Server-Status-Misconfiguration-nuclei-script

<h3>Description :</h3>
The server-status page allows server administrators to find out how well their server is performing. This is a HTML page that gives the current server statistics such as the server version, up time,cpu, ram, and information about requests made to the server.

<h3>Impact :</h3>
If the /server-status is exposed to the public then there is something wrong. This page can be used to monitor users GET requests for sensitive information. If the applications sends CSRF tokens, API keys, or anything else in a GET request then attackers will be able to see it. 

<h3>Tool :</h3>
https://github.com/projectdiscovery/nuclei

<h3>Refrence :</h3>
https://medium.com/@ghostlulzhacks/apache-server-status-a70abed83f5a
