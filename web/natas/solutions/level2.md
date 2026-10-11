# Natas Level 2

## Connection

URL: http://natas2.natas.labs.overthewire.org

## Credentials

- Username: `natas2`
- Password: `vsDOxoXyq3wckCP1ZmTZ71ngIA606odB`

## Solution

Once we inspect the HTML source we can see that there is an image referenced at `/files/pixel.png`. Since the `/files` directory is accesible, directory listing is enabled so every file that is
in it is visible. Besides `pixel.png`, there is a file called `users.txt`. This file contains passwords for different users, one of them being `natas3`.

## Takeaway

Directory listing exposed sensitive files. 

## Password

`K30JrSRHzjxq3paUQuwozY4MNvmNFyhI`
