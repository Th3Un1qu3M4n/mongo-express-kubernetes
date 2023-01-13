# mongo-express-kubernetes


## Application Overview:

 We will be using a mongo-express app which is a WebUI created in ExpressJS to interact with mongoDB and deploy it in Kubernetes cluster. We will be using Minikube to simulate the Kubernetes on local machine.

- There will be 3 replicas of web app.
- The user can access the application at the url provided by the service.
- There will be one mongoDB instance running on port 27017

![image](https://user-images.githubusercontent.com/57266167/212315949-01a77143-a8c1-48c6-a36a-576b8fc87299.png)

### Steps to Deploy the Application:

- Start the minikube cluster

![image](https://user-images.githubusercontent.com/57266167/212315965-29b56e51-e5cd-48a4-86c5-43501036db24.png)

- Write the yaml files, we will be writing two yaml files one for mongoDB server and the other for web server.

- Now run the following commands to apply the configuration and start application in the Kubernetes Cluster.
![image](https://user-images.githubusercontent.com/57266167/212315997-712de75b-2875-4d90-9791-8dd947727388.png)


- We can run the following commands to get the status of the services, deployments and pods.
![image](https://user-images.githubusercontent.com/57266167/212316021-934130c2-b977-4102-b150-39e470976b31.png)

- We can use the minikube command to get the url of the application.
- Upon opening the url in the browser, we can see that the application is being served.
![image](https://user-images.githubusercontent.com/57266167/212316057-a2d99279-d14b-49b5-a808-22543ba573a6.png)


