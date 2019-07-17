# 启动mongo数据库
```
/*容器安装mongo数据库*/
#sudo docker pull mongo:4.0

docker run --rm --name mongo_blog_container -d -p 127.0.0.1:27017:27017 mongo:4.0
```