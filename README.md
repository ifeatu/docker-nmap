# docker-nmap

## NMap version 6.49BETA4-1

This is a dockerized version of [Nmap](http://nmap.org/ "Nmap: the Network Mapper - Free Security Scanner").

The easiest way to use `nmap` is to create an alias.

```bash
alias nmap='docker run -it --rm golden/nmap'

nmap -p 443 -v -A github.com
```
