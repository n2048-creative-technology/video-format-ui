

```
docker build -t video-edit .

docker rm -f video-edit
docker run -d --name video-edit -p 8000:80 -v $(pwd)/html/:/usr/share/nginx/html/ video-edit:latest

```


