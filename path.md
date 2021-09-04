## Create a python file

```python
print("You successfully runned Docker Python Image 3")
```

## Craete a docker file

```js
FROM python
WORKDIR /app
COPY . .
CMD ["python", "main.py"]
```

## Commands

```js
docker build .
```
### or

```js
docker build -t pytest1 -f Dockerfile .
```
### see all images
```js
docker image ls
```

### run docker iamge by image id
```js
docker run 3488449c7e59
```

### remove docker iamge by image id
```js
docker image rm -f afc641bcef16
```

### give tag name fedora/httpd:version1.0 to docker iamge by image id 0e5574283393
```js
docker tag 0e5574283393 fedora/httpd:version1.0
```

### remove docker iamge by image id
```js
docker image rm -f afc641bcef16
```


