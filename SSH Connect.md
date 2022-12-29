# Quick Note:
**I have never used SSH before, so unfortunately I will just be copying and pasting and trying to fix any grammar and spelling mistakes I can identify.**

# How to connect your XinaA15 device through SSH

Configure the SSH to be connected to the port: `22` (this should be 22 by default)

If asked for a SSH password, input the default password: `alpine` (this should not be changed)

After that, put: `ssh root@(your IP)`

# If you need to repair your SSH password temporarily:

Input the following command and enter:

`ssh-copy-id -i $HOME/.ssh/id_ rsa` 

Put: `ssh root@(your IP)`
