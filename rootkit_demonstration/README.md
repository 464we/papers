# Linux Rootkit Desmonstration Codes

These codes has study purposes and was demonstrated on [Sinergia Hangout](https://www.youtube.com/watch?v=NoWDcYu1cw0) on October 2nd. 

## hellokernelworld

A simple hello world on kernel mode using LKM

## get_sys_call_table

A simple LKM that demonstrate how to get sys_call_table base address dinamically

## sys_call_hijack

A module that demonstrate how to hijack a sys_call

## read_hook

A module to demonstrate how to hide files contents using a hook on read()

## tiny_rootkit

A LKM rootkit for demonstration purposes.

Features:
- Give root on hooked setreuid()
- Launch a ICMP port-knocking backdoor

## Disclaimer

If you are searching for a real world rootkit see [Reptile](https://github.com/f0rb1dd3n/Reptile)
