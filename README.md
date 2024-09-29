# scrape-master
added:  
- poetry
- devcontainer
- selenium grid
# Usage
configure .env file:
```bash
cp .env.sample .env
```
start selenium grid:  
[doc](https://hub.docker.com/r/selenium/standalone-chrome)
```bash
docker run --rm -d -p 4444:4444 -p 7900:7900 --shm-size="2g" selenium/standalone-chrome:latest
```
start the scraper:
```bash
make
```
## optional:
see the browser working:
[http://localhost:7900/?autoconnect=1&resize=scale&password=secret](http://localhost:7900/?autoconnect=1&resize=scale&password=secret)
see the grid console:
[http://localhost:4444/ui/#](http://localhost:4444/ui/#)
# About
This project is based/forked from 
[scrape-master](https://www.youtube.com/watch?v=-IAwW3pUEew)