# mysql-flask-kubernetes

Build the image using the command:

docker build -t yourapp .

Push the image to your repository, change the values.yaml ans execute the helm command to deploy the chart on your kubernetes cluster.

helm install flaskapi charts/flask/ -f values.yaml -n <your_namespace>
