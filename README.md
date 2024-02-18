build
```bash
docker build . -t ctnelson1997/cs571-s24-hw4-api
docker push ctnelson1997/cs571-s24-hw4-api
```

run
```bash
docker pull ctnelson1997/cs571-s24-hw4-api
docker run --name=cs571_s24_hw4_api -d --restart=always -p 58104:58104 -v /cs571/s24/hw4:/cs571 ctnelson1997/cs571-s24-hw4-api
```

run fa
```bash
docker pull ctnelson1997/cs571-s24-hw4-api
docker run --name=cs571_fa_s24_hw4_api -d --restart=always -p 59104:58104 -v /cs571_fa/s24/hw4:/cs571 ctnelson1997/cs571-s24-hw4-api
```