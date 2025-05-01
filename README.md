# Blue-Green Deployment of Node.js Application using Docker and Kubernetes

## Overview

This project demonstrates the deployment of a containerized Node.js application with a MongoDB backend, two frontend variants (Basic and Enhanced), and a blue-green deployment strategy implemented using Kubernetes on Minikube.


# Prerequisites   

Docker Desktop  
Minikube  
kubectl    
Helm  
Node.js  
Git  

# Backend Setup 
Navigate to backend directory 

Install dependencies  

cd backend   
npm install  

Create .env file with:  
PORT=5000  
MONGO_URI=your-mongodb-connection-string  

Start backend server   
npm install express   
npm start 

![image](https://github.com/user-attachments/assets/d5cb3e80-f071-4080-a6b4-dbf83e36e7e2) 

# Frontend Setup  

1. Setup Blue Frontend 

cd frontend-blue   '
npm install    

Create .env file:  
PORT=3100    
MONGO_URI=your-mongodb-connection-string     

2. Start blue frontend
  
npm start 

![image](https://github.com/user-attachments/assets/ad1f2ebc-2b37-4592-8aa5-ab34fbd2909e) 

![image](https://github.com/user-attachments/assets/2be22b74-726d-44fa-8bd4-01ed9adbfdab)   

3. Setup Green Frontend  
   
cd frontend-blue    
npm install     

Create .env file:   
PORT=3200      
MONGO_URI=your-mongodb-connection-string  

4. Start blue frontend

npm start  

![image](https://github.com/user-attachments/assets/8c858708-4815-44c8-bc39-52b4ed3e6362)   

![image](https://github.com/user-attachments/assets/a3a5464a-1ec6-4305-ae49-074499a02538)



   






