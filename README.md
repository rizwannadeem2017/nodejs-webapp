# sample nodejs-webapp

1. build docker file
1.1 docker build -t .

2. update docker image in kubernetes deployment manifest file. 
2.1 edit deployment.yaml file and update the docker image name. 

3. run kubernetes deployment command to deploy the application.  
3.1 kubectl create -f deployment.yaml 
3.2 kubectl get svc,ingress 

4. browse the application http://myapp 
