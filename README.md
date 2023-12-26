# docker_php_apache_mysql

## step 1: build image

```
    docker build -t my_php_image 
```

## step 2: run container

```
    docker run -i --rm -v ${PWD}:/var/www/html --name my_php_container -p 3000:80 my_php_image
```