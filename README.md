## HTTP/1.1 Web Server
Hobby web server for processing HTTP/1.0 and HTTP/1.1 requests

#### Compile & Run
1. In terminal, `cd` to project root
2. Compile with `$ make`
3. `$ make clean` to clean the project directory

#### Example
* From project root, start the server using the `./server` command
* Once running, simple requests can be made:
```
$ telnet {hostname} 4077
  GET {filename} HTTP/1.1
  Host: {hostname}
  Expect: 100-continue  
```
