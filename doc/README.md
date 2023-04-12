```shell
sudo docker build -t chatgpt-web .

# 前台运行
sudo docker run --name chatgpt-web --rm -it -p 127.0.0.1:3002:3002 --env OPENAI_API_KEY=your_api_key chatgpt-web

# 后台运行
sudo docker run --name chatgpt-web -d -p 127.0.0.1:3002:3002 --env OPENAI_API_KEY=your_api_key chatgpt-web

# 运行地址
http://localhost:3002/

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

https://bypass.churchless.tech/api/conversation
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

sudo docker tag chatgpt-web yiluxiangbei/chatgpt-web
sudo docker push yiluxiangbei/chatgpt-web

sudo docker-compose up -d
sudo docker-compose ps
sudo docker-compose logs -f

docker exec -it docker_app_1 sh
```