`rpi4b_tunx.x` forwards client's `ssh` port to a port e.g. 3001 on the remote host. The user can then login into the client by executing the following command on the remote host.
```
ssh -p 3001 localhost
````
This allows a client with dynamic IP to become accesible through the remote host.

<b>NB</b> 
* ver 0.4 suits those with no sudo access on remote host
* ver 0.3 requires `netcat` install