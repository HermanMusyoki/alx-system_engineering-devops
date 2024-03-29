# 0x05. Processes and signals
## Process
A process can be thought of as an instance of a program in execution. We called this an ‘instance of a program’, because if the same program is run lets say 10 times then there will be 10 corresponding processes.

In Linux processes can be of two types:
- Foreground Processes
depend on the user for input
also referred to as interactive processes
- Background Processes
run independently of the user
referred to as non-interactive or automatic processes

Process States in Linux
A process in Linux can go through different states after it’s created and before it’s terminated. These states are:
- Running
- Sleeping
Interruptible sleep
Uninterruptible sleep
- Stopped
- Zombie
## Signal
A signal is an event generated by the UNIX and Linux systems in response to some condition. Upon receipt of a signal, a process may take action.
There are two types of signals:
- Maskable: signals which can be changed or ignored by the user (e.g., Ctrl+C).
- Non-Maskable: signals which cannot be changed or ignored by the user. These typically occur when the user is signaled for non-recoverable hardware errors.
