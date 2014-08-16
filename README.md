plossmon
========
Usage:
plossmon

Packet Loss Monitor - This monitor runs in a loop and will ping any number of hosts with a configurable number of packets at a specified interval.  Output is only generated to stdout on iterations that have missing packets, unless -v is specified as an option.  All iterations, including those without any packets lost, are recorded to a log file.  The monitor will only allow one instance running per user.

If sleepwatch (https://github.com/tgrey1/sleepwatch) is installed in your path, a user confirgurable lockfile will automatically be used.  Removing the lockfile will force a new iteration of pings to start.
