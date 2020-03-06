# README

*Just for demo purposes.*

For use with https://github.com/thoughtworks/build-your-own-radar

```bash
$ docker pull wwwthoughtworks/build-your-own-radar
$ docker run --rm -p 8080:80 -e SERVER_NAMES="localhost 127.0.0.1" wwwthoughtworks/build-your-own-radar
$ open http://localhost:8080
```

In the box add the link to the raw csv file (click raw on the file and copy the link).


Be aware that when you change the csv file, it takes some time for the raw file to update, something with caching on raw.githubusercontent.com

