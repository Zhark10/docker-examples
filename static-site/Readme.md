### 1) Build our static HTML image using the build command below.
```bash
$ docker build -t webserver-image:v1 .
```

### 2) You can view a list of all the images on the host using
```bash
$ docker images
```

### 3) Launch our newly built image providing the friendly name and tag.

```bash 
$ docker run -d -p 80:80 webserver-image:v1
```

### 4) Once started, you'll be able to access the results of port 80 via
```bash
$ curl docker
```