# ECEN5623-Ex3-5

## 5) Watchdog timers, timeouts and timer services – First, read this overview of the Linux Watchdog Daemon and the Linux manual page on the watchdog daemon - https://linux.die.net/man/8/watchdog . Also see the Watchdog Explained.

### A) Describe how it might be used if software caused an indefinite deadlock.

### B) Next, to explore timeouts, use your code from #2 and create a thread that waits on a MUTEX semaphore for up to 10 seconds and then un-blocks and prints out “No new data available at <time>” and then loops back to wait for a data update again. Use a variant of the pthread_mutex_lock called pthread_mutex_timedlock to solve this programming problem.
