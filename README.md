/bin/synctime:
#!/usr/bin/env python
.....................

/bin/timeusync:
#!/bin/sh
kill -9 `pgrep python` > /dev/null 2>&1;/bin/synctime
