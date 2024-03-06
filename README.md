# pico-ducky-scripts
Rubber ducky scripts that can work with raspberry pico as an HID.
The payload file its a reverse shell code that opens a shell with netcat listening.
Replace the listener machine [IP] and [PORT]. </br>
Try this command `stty raw -echo;(stty size; cat) | ncat -lvnp [PORT]` if the normal listening did 
not worked.
