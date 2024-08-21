# PidLock.py
System level process lock

A Utility script with for safely locking running process using it's id.
Will atomically register lock and unregister lock.

#### Usage
To obtain lock, call registerPid() from parent:

`registerPid(<process id>)`

Release lock by calling unregisterPid():

`unregisterPid(<process id>)`
