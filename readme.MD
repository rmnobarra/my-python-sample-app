## A simple python app for test purposes.

### BUILD LOCALLY:
```bash
docker build --tag my-python-sample-app .
```

### RUN:
```bash
docker run --name python-sample-app -p 5000:5000 my-python-sample-app -d
```
### TAGGING:
```bash
docker tag my-python-sample-app <REPO>/my-python-sample-app:1.0
```
### PUSH TO REGISTRY:
```bash
docker push <REPO>/my-python-sample-app:1.0
```
### BUILD WITH TAG:
```bash
docker build -t <REPO>/my-python-sample-app:1.0
```

### RUN FROM REGISTRY:
```bash
docker run --name python-app -p 5000:5000 rmnobarra/my-python-sample-app:1.0
```


