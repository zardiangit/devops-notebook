---
id: eessy3szv3ajijb5cgp58zh
title: Sudo
desc: ''
updated: 1649159675840
created: 1649159675840
---

## Setup
---

To setup sudo the user must switch to `su` account.


The sudo config. should always be edited with the `visudo` command.  
- the default text editor for *visudo* is `vi`.  

To switch the default editor use
>EDITOR=nano visudo

Now to edit the `/etc/sudoers.d/<your_username>`
>`EDITOR=nano visudo -f /etc/sudoers.d/<your_username>`

To allow a user to gain full root privileges when they precede a command with sudo, add the following line:
>USER_NAME   ALL=(ALL:ALL) ALL

To allow a user to run all commands as any user but only on the machine with hostname HOST_NAME:
>USER_NAME   HOST_NAME=(ALL:ALL) ALL

Setting required permissions
>chmod -c 440 /etc/sudoers.d/<your_username>

- More details:  
<https://wiki.archlinux.org/title/sudo>