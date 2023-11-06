# Interview-Task-K8s-
In a typical job interview process, the technical test is a crucial stage that evaluates a candidate's practical skills and knowledge relevant to the job position. This stage usually consists of a series of tests or exercises designed to assess the candidate's ability to solve technical problems and perform tasks that are directly related to the role they are applying for. Here is a test home screen instructions how it look

TEST INSTRUCTIONS: 

Thanks for your interest in joining the Home Office team and for taking the time to complete this online technical evaluation that is designed to enable the Home Office recruitment team to better understand where your strengths are.
This online evaluation includes one of the following modules:
* Multiple or Single Choice Questions
* One or more coding challenges
* Diagram challenge
* Project challenge

Good luck, have fun, and thanks again for your interest in joining the Home Office team!

Notes:

• You can access the instructions panel on the top left side of your screen where you will be able to see all these instructions again.

• A fully functional IDE is provided for you for the coding Challenges.

• You can run/debug your code inside the integrated console for the Coding Challenges.

DESCRIPTION: 

To begin, kindly provide your login credentials, including your email address. Once this information is submitted, you will be prepared to initiate the test. In certain instances, practice tests may be available to help you familiarize yourself with the format of the actual test. When you are ready to commence the official examination, the timer will be activated, and you must complete the test within the allocated time frame before submitting your responses.

TASK 1:

Kubernetes Task:

You need to deploy an application on Kubernetes. Create and complete the deployment.yaml file in order to solve this challenge. Do not create reasources from the CLI, all of them are deleted when the tests are run.

Your task is to:

* ﻿﻿Create a new namespace hackajob-challenge

* ﻿﻿Deploy a pod using the nginx:stable image from Docker hub in the namespace hackajob-challenge with a name of application, container name of nginx and a label 
  of app=MyApp 

* Finally create a service named application-service with type LoadBalancer, that is forwarding port 80 to the pod tagged with label app-MyApp on port 8081

COMMAND: 

kubectl apply -f deployment.yaml







