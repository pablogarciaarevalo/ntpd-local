# ntpd Local
Create a ntp server based on the local clock, without the required external ntp servers connection

## Getting Started

Docker container at [https://hub.docker.com/r/pablogarciaarevalo/ntpd-local/](https://hub.docker.com/r/pablogarciaarevalo/ntpd-local/)

## Running

```
> docker run --name ntpd -d -p 123:123/udp pablogarciaarevalo/ntpd-local
```
