# chat-server

- Simple TCP server in golang

# Working

- Get this code first.

  ```golang
    go get github.com/Smellyslab/go-chat-server
  ```
  
  ```golang
    import "github.com/smellyslab/go-chat-server"
    
    func main() {
     
      chatserver.New("9999") // change the 9999 to your port...
    
    }
  
  
- Then create clients by using `telnet`.

  ```golang
     telnet 127.0.0.1 8080
  ```



=====================================================================

Simply turned the code into a package for go

all credit to the original creator for writing this

=====================================================================
