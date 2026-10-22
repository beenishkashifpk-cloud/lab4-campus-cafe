# HTTP observations (Lab 4, Task 1)

| Question | My answer |
|----------|-----------|
| Request method for index.html | GET |
| Status code with Disable cache ticked | 200 |
| Status code on a normal reload | 304 |
| Status code for /nothing-here.html | 404 |
| Value of the Content-Type response header | text/html; charset=UTF-8 |
| Remote Address (IP and port) | 127.0.0.1:5500 |
| Protocol in the address bar (http or https) | http |

## Why is this address http and not https?
HTTPS protects data while it travels across a network, so other people cannot read or change it. My traffic to 127.0.0.1 only goes to my own computer and never leaves it, so encryption is not needed here.
## Screenshot
![Network tab headers for index.html](images/task1-headers.png)