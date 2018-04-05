# ForkedWiringPi
Original: http://wiringpi.com/, in the ```upstream_repository``` branch.

## How to sync with original WiringPi

```console
$ cd /path/to/ForkedWiringPi
$ git remote add upstream git://git.drogon.net/wiringPi
$ git checkout -b upstream_repository origin/upstream_repository
$ git fetch upstream
$ git merge upstream/master
```
