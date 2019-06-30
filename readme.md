```bash
yarn
yarn webpack client.js --mode development

node server.js #ポート9090でリッスンします

docker build -t helloworld/envoy -f ./envoy.Dockerfile .
docker run -d -p 8080:8080 helloworld/envoy

yarn static -p 8081
```

http://localhost:8081/

[1.png](1.png)
