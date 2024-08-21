# PidLock.py
System level process lock

A Utility script with for safely locking running process using it's id.
Will ensure only the process that has obtained the lock with registerPid() is the only one that runs.

#### Usage
To obtain lock, call registerPid() from parent:

`registerPid(<process id>)`

Release lock by calling unregisterPid():

`unregisterPid(<process id>)`
