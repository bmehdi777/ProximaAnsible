# ANSIBLE 

## Prerequisites

You need to push your public ssh key to server :

Copy your id_rsa.pub to authorized key in the server.

## To test it out

You can ping every machines like this :

> ansible -i hosts -m ping all

- "hosts" is the file with your inventory