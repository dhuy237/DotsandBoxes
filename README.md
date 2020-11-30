# DotsandBoxes

## Prerequisites
```pip install -r requirements.txt```

## Usage
Run `server.py` and input the `Host` and `Port`.  
In this example: `Host`: `localhost` and `Port`: `8000`.
```
$ python server.py
STARTING SERVER ON LOCALHOST
Host:Port (localhost:8000): localhost:8000
```

Then open 2 terminals to run the client.  
Input the `Address of Server` the same with the `Host:Port` above.
```
$ python Boxes.py
pygame 2.0.0 (SDL 2.0.12, python 3.7.9)
Hello from the pygame community. https://www.pygame.org/contribute.html
Address of Server: localhost:8000
Boxes client started
```
On the `server.py` terminal, you will get this output:
```
new connection: <__main__.ClientChannel connected 127.0.0.1:55967 at 0x1f9d4faa708>
```
It means there is a client connected to the server. Do the same with the second client.

Finally, play.