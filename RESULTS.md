##Setup
I use
System: xv6 (x86)
Scheduler: Lottery Scheduler (using total tickets winner has been decided)
syscall: settickets updates the calling process ticket count
Rule: must be >=1 otherwise syscall returns -1
Default tickets: new processes start wirh 1 ticket


