# How to connect your XinaA15 device through SSH
I have never used SSH before, so unfortunately I will just be copying and pasting and trying to fix any grammar and spelling mistakes I can identify.

Configure the SSH to be connected to the port: **22**

Configure the SSH password to be a free root password, the default password is: **alpine**

Put root @(your IP)

# If you need to repair your SSH password temporarily:

Input the following command and enter:

`ssh-copy-id -i $HOME/.ssh/id_ rsa` 

Put root @(your IP)
