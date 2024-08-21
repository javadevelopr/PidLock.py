# PidLock.py
System level process lock

A Utility script with functions to create system level locks in a safe way for running processes.
Will ensure only the process that has obtained the lock with registerPid() is the only one that runs.

#### Usage
To obtain lock, call registerPid() from parent:

`registerPid(<process id>)`

Release lock by calling unregisterPid():

`unregisterPid(<process id>)`
