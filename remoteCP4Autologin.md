The **Autologin**-Feature is really easy to use! Just edit your remoteCP URL a little bit, to automatically login as guest with the permission you setup for the **guest** user. Just edit your URL from this:
```
http://www.mydomain.com/remoteCPpath/index.php
```

To this:
```
http://www.mydomain.com/remoteCPpath/index.php?autologin=true&serverid=1
```

To select different servers, just change the value behind **&serverid=** to the **serverid** from your **/xml/servers.xml**.