# IoT Project with AWS Cloud Platform

## Project Overview

* Push [jet engine data](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan) to AWS
* Record those data inAWS IoT and Visualize them
* Use AWS services, such as MQTT,Lambda Function, SNS
* Programming Language - Python
_____________________________________________________________________________________________________________
## Environment SetUp

* AWS Account
* Python SDK for AWS IoT
* Anaconda Powershell 
____________________________________________________________________________________________
## Data
* jet engine data
* real time weather using API
_______________________________________________________________
## Procedures

* Register a thing and download a connection kit by following the [insturctions](https://docs.aws.amazon.com/iot/latest/developerguide/what-is-aws-iot.html)
* Subscirbe and Publish Process with AWS, where computer is Publisher and AWS IoT is Subscriber
* Prepare the data
* DynamoDB rule is setup to visualize and contents are published by following the [insturctions](https://docs.aws.amazon.com/iot/latest/developerguide/what-is-aws-iot.html)
* Two Engine Data were displayed at DynamodB
* SNS rule is applied for sending emails of the result

![image](https://user-images.githubusercontent.com/50255936/110677678-66294380-8210-11eb-97e6-d920697c34fd.png)

* Test with Real time weather API

### DynamodB Result and Email SNS which topic is connected with Lambda function for weather data
![image](https://user-images.githubusercontent.com/50255936/110676998-991f0780-820f-11eb-971a-77a077a1c67f.png)

![image](https://user-images.githubusercontent.com/50255936/110677279-f3b86380-820f-11eb-819e-8b22663edb82.png)

### Published Engine Data using Shadow and Lambda Function for Email Alert

![image](https://user-images.githubusercontent.com/50255936/110677567-442fc100-8210-11eb-9fbd-53be8d83f7a8.png)

