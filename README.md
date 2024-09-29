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
```bash
docker run --rm -d -p 4444:4444 -p 7900:7900 --shm-size="2g" selenium/standalone-chrome:latest
```
start the scraper:
```bash
make
```
# About
This project is based/forked from 
[scrape-master](https://www.youtube.com/watch?v=-IAwW3pUEew)