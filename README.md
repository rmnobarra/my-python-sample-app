##A simple python app for test purposes.

###BUILD LOCALLY
docker build --tag my-python-sample-app .


###RUN
docker run --name python-sample-app -p 5000:5000 my-python-sample-app -d

###TAGGING
docker tag my-python-sample-app <REPO>/my-python-sample-app:1.0

###PUSH TO REGISTRY
docker push <REPO>/my-python-sample-app:1.0

###BUILD WITH TAG
docker build -t <REPO>/my-python-sample-app:1.0




