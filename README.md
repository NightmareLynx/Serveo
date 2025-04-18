# Serveo (Ngrok Alternative)
Serveo is an excellent alternative to ngrok. Serveo was inspired by ngrok and attempts to serve many of the same purposes. The primary advantage of Serveo over ngrok is the use of your existing SSH client, so there's no client application to install.

```
parameter : [http/tcp] [local port] [option]

  http  80 0             //localhost:80 forward to public https
  tcp 4869 0             //random tcp port forwarding
  tcp 4869 1945          //custom tcp port forwarding
  ```

  # Install For Linux
`git clone https://github.com/NightmareLynx/Serveo`
  
 ## Example
For random http subdomain
`serveo http 80 0` 
  
For change http subdomain
`serveo http 80 change` 
  
For custom port
`serveo http 80 4869` 


# Note:
Hey Anons,
Serveo is a free-to-use (open-source) tunneling tool that exposes your localhost to the internet through a secure tunnel (link). Please do not misuse this tool.
It is intended only for testing and educational purposes. If you still choose to use it in real scenarios, make sure to have proper permissions and documentation.

**And always remember — no one is 100% secure.**
