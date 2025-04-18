# serveo
Serveo is an excellent alternative to ngrok. Serveo was inspired by ngrok and attempts to serve many of the same purposes. The primary advantage of Serveo over ngrok is the use of your existing SSH client, so there's no client application to install.

```
parameter : [http/tcp] [local port] [option]
  http  80 0             //localhost:80 forward to public https
  tcp 4869 0             //random tcp port forwarding
  tcp 4869 1945          //custom tcp port forwarding
  ```
  
  
 ## Example
request random http subdomain
`serveo http 80 0` 
  
request change http subdomain
`serveo http 80 change` 
  
request custom port
`serveo http 80 4869` 
  
### Linux
`wget https://raw.githubusercontent.com/milio48/serveo/master/serveo.sh`

### Windows
u can download exe, but arg not supported cause compiled by winrar

if u run from source, u can run with arg. but u must run in same folder with library.
> sorry in windows version, haven't supported to reverse shell with nc. maybe have problem in ssh library.
> please contrib
