# AngularJS
Get start angular and docker 

### Building your image
```
docker build -t angularjs .
```

### Run the image
```
docker run --name exampleangularjs -d -p 8080:80 -v $(pwd):/usr/share/nginx/html angularjs
```

### Ready 

```
localhost:8080
```
