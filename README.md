```
go get -u github.com/swaggo/swag
docker-compose up
go run .

http://localhost:1323/api/v1/wallets
http://localhost:1323/swagger/index.html

cd wallet
go test -v -cover 

docker network ls
docker run --network=go-kbtg-challenge_8_default -p 1324:1323 aiyaraaiya/go-kbtg-challenge_8:v1.0

docker build --no-cache -t aiyaraaiya/go-kbtg-challenge_8:v1.0 .
docker run -p 1324:1323 aiyaraaiya/go-kbtg-challenge_8:v1.0
```

```
docker-compose up -d

#docker-compose run instead of docker
localhost:1324/api/v1/wallets

docker-compose down --rmi local
```