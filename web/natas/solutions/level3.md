# Natas Level 3

## Connection

URL: http://natas3.natas.labs.overthewire.org

## Credentials

- User: `natas3`
- Password: `K30JrSRHzjxq3paUQuwozY4MNvmNFyhI`

## Solution

We get a hint on a comment in the HTML source: `<!-- No more information leaks!! Not even Google will find it this time... -->`. Visiting `/robot.txt` revealed a `Disallow` entry for a 
`/s3cr3t` directory. In said directory, where directory listing is enabled (!!), there is a `users.txt` file that contains the password.

## Takeaway

`/robot.txt` does not restrict access to the paths crawlers should not index. 

## Password

`JDrPnuZAKyl6MkiqQGFIddrqpvgOASth`
