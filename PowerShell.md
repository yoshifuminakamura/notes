At 2023/10/20

The following issue with PowerShell SSH that had been occurring on a specific host for quite some time 
```
chan_shutdown_read: channel 1: shutdown() failed for fd 7 [i0 o0]: Not a socket
debug1: get_agent_identities: ssh_fetch_identitylist: communication with agent failed
```
has been resolved with the following update. 

https://github.com/PowerShell/Win32-OpenSSH/releases/tag/v8.9.1.0p1-Beta
`OpenSSH-Win64-v8.9.1.0.msi`

Finally, agent forwarding with PowerShell works on all hosts.
