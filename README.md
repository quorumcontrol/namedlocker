# Named Locker

Named locker implments a struct that has methods that create namedspaced RWMutex locks.
It is up to the user to delete the unused locks (or else there is a memory leak).