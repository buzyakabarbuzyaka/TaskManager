Запуск из текущей директории  
`run command:`
```
uvicorn app.main:app --host 0.0.0.0 --port 8080
```
`docker run`
```
docker build -t myimage .
docker run -d --name mycontainer -p 80:80 myimage
```