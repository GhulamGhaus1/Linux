# Creating a User Pool in AWS Cognito
(https://app.tango.us/app/workflow/8105f4ff-f863-4cf8-b065-bc31ef28a3e2?utm_source=markdown&utm_medium=markdown&utm_campaign=workflow%20export%20links)

__Creation Date:__ November 1, 2023  
__Created By:__ Ghulam Ghaus  



***




## # [Aws cognito](https://us-east-1.console.aws.amazon.com/console/home?region=us-east-1#)
**Amazon Cognito is a service provided by AWS that allows developers to add user sign-up, sign-in, and access control to their web and mobile apps. It offers OAuth 2.0 tokens for user authentication, which can be exchanged for temporary AWS credentials through an identity pool. These credentials can then be used to access AWS APIs and services like Amazon S3 and Amazon DynamoDB.**


### 1. Select cognito from services
![Step 1 screenshot](https://images.tango.us/workflows/8105f4ff-f863-4cf8-b065-bc31ef28a3e2/steps/3b973b6a-b709-4183-a70c-f273ca207900/d865b790-53ae-46e7-b139-d5002b2a4b09.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=376&mark-y=160&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz01NyZoPTIwJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D)


### 2. Click on Create user pool
![Step 2 screenshot](https://images.tango.us/workflows/8105f4ff-f863-4cf8-b065-bc31ef28a3e2/steps/5113f37e-0563-4e6b-9cb1-0db0ffa66607/cafc336b-367a-44ec-a773-0c99c2930dc9.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=727&mark-y=275&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz0xMjkmaD0zMiZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)


### 3. You can choose to have users sign in with an email address, phone number, username
or preferred username plus their password.
![Step 3 screenshot](https://images.tango.us/workflows/8105f4ff-f863-4cf8-b065-bc31ef28a3e2/steps/a9587599-fa67-40e2-b701-71deefd383e2/7e35c8a8-ae6f-450c-9466-1f8db82381ec.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=861&mark-y=611&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz02NSZoPTMyJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D)


### 4. 1. Multi-Factor Authentication (MFA) increases security for your end users. Phone numbers
must be verified if MFA is enabled. We choose Off for this lab.
![Step 4 screenshot](https://images.tango.us/workflows/8105f4ff-f863-4cf8-b065-bc31ef28a3e2/steps/c0f111f7-dc01-462c-b720-a95e82cf8426/5e3e2ea3-8394-4e5c-b2f0-9df6c8d99a87.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=861&mark-y=703&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz02NSZoPTMyJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D)


### 5. Click on Next
![Step 5 screenshot](https://images.tango.us/workflows/8105f4ff-f863-4cf8-b065-bc31ef28a3e2/steps/9cd7c000-d1b6-4d7b-94ed-6d10e28d8b46/bccaef57-3a9e-4382-a621-c013a782dcce.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=861&mark-y=703&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz02NSZoPTMyJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D)


### 6. You can send emails from an SES verified identity. Before you can send an email using
Amazon SES, you must verify each identity that you're going to use as a From, Source,
Sender, or Return-Path address to prove that you own it. For now, we leave it blank.
![Step 6 screenshot](https://images.tango.us/workflows/8105f4ff-f863-4cf8-b065-bc31ef28a3e2/steps/94e6a862-63c6-44a3-aea8-242a52b3b9f4/56d1904d-84f4-4256-91d0-d2e157ab21ac.png?crop=focalpoint&fit=crop&fp-x=0.5040&fp-y=0.4834&fp-z=1.0979&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=620&mark-y=274&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0xOSZoPTE5JmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D)


### 7. Click on Next
![Step 7 screenshot](https://images.tango.us/workflows/8105f4ff-f863-4cf8-b065-bc31ef28a3e2/steps/3e51dc9d-0059-468f-946c-129bb9087a82/e5f9a479-414e-483d-965e-2920593b04a4.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=861&mark-y=703&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTMlMkNGRjc0NDImdz02NSZoPTMyJmZpdD1jcm9wJmNvcm5lci1yYWRpdXM9MTA%3D)


### 8. Click on Create user pool
![Step 8 screenshot](https://images.tango.us/workflows/8105f4ff-f863-4cf8-b065-bc31ef28a3e2/steps/cd681292-349f-411e-9a3c-3f7c941c1f86/0693fe3c-a7a0-4cdb-8742-2bc1297ac2a7.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&fp-z=2.0000&w=1200&border=2%2CF4F2F7&border-radius=8%2C8%2C8%2C8&border-radius-inner=8%2C8%2C8%2C8&blend-align=bottom&blend-mode=normal&blend-x=0&blend-w=1200&blend64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL21hZGUtd2l0aC10YW5nby13YXRlcm1hcmstdjIucG5n&mark-x=995&mark-y=1021&m64=aHR0cHM6Ly9pbWFnZXMudGFuZ28udXMvc3RhdGljL2JsYW5rLnBuZz9tYXNrPWNvcm5lcnMmYm9yZGVyPTQlMkNGRjc0NDImdz0yNTgmaD02NCZmaXQ9Y3JvcCZjb3JuZXItcmFkaXVzPTEw)

<br/>

***
Created with [Tango.us](https://tango.us?utm_source=markdown&utm_medium=markdown&utm_campaign=workflow%20export%20links)
