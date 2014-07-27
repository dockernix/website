# Create container
```bash
docker.io run -d -p 80 --name website -v $PWD/website:/var/www/html/website:ro kobrinartem/nginx nginx
```
