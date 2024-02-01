Task1: Start a aws ec2 instance
Task2: Install minikube with kubectl on it
Task 3: create yaml file for all five deployments and 4 services.
task 4: Create kubernetes deployment with the yaml files
task 5: create the service with service yaml file
task 6: allow all ports to security group as well as expose from the node.


<img width="914" alt="image" src="https://github.com/MdRasel0/assignment-3/assets/52493009/93b798a9-19c0-495c-b22d-68a840a888e7">
<img width="934" alt="image" src="https://github.com/MdRasel0/assignment-3/assets/52493009/591c0cd8-239b-4de0-8c89-9a6f2ce2ad92">




Output1: pods and service creation

![image](https://github.com/MdRasel0/assignment-3/assets/52493009/5a439c9e-10e8-448d-8c60-f07629e505a0)

 
Output 2: Deployments 

![image](https://github.com/MdRasel0/assignment-3/assets/52493009/2b002964-b93b-4b57-8430-a12566c5d085)

 
Output 3: Service

 ![image](https://github.com/MdRasel0/assignment-3/assets/52493009/49509ca8-3f98-4c9b-831a-83448a2e6aef)

 
Fig: 5 tier voting app deployed on minikube
To access the deployed application:
Need to hit the IP address on the browser with appropriate ports for voting port will be IP:30004 and for result access will be done by IP:30005. 
•	The app will work on below:
•	Vote will cast on python voting app
•	Redis will cache and deliver the result to the .net worker.
•	.net worker app then will communicate with the postgresdb
•	After that result will take the acess of db and will show the voting results.
Github Link: https://github.com/MdRasel0/assignment-3/tree/main 
