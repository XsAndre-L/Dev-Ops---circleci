# Dev-Ops---circleci

## Project Overview

This is the Dev-Ops project that connects an angular Front-End with an Express backend. included is the CI process and documentation on this process.

## Access The App

Frontend (hosted on S3 Buckit):  
http://ecommerse-frontend---angular941266980980.s3-website-us-east-1.amazonaws.com

Working app:
![image](/Docs/screenshots/Working%20App.png)

## AWS infrastructure for the web application

### S3 Buckit ( Front-End )

![image](/Docs/screenshots/Service_S3.png)

### EB Environment ( Backend )

![image](Docs/screenshots/EB_environment.png)
![image](Docs/screenshots/EC2_env_variables.png)

### RDS ( Database )

![image](Docs/screenshots/Service_RDS.png)

---

## Configuring Continuous Integration Pipeline with Github

Successfull pipeline
![image](Docs/screenshots/CircleCi_Pipeline.png)

Build Stage:
![image](/Docs/screenshots/CI_BUILD.png)

Test Stage:
![image](/Docs/screenshots/CI_TEST.png)

Deploy Stage:
![image](/Docs/screenshots/CI_DEPLOY.png)

All secrets are found within the CI Software
![image](Docs/screenshots/CircleCi_Secrets.png)

---

## Installation

### Step 1: Software

make sure you have the following installed:  
aws cli  
eb cli

### Step 2: Clone Repository

```bash
git clone --recurse-submodules https://github.com/XsAndre-L/Dev-Ops---circleci.git
```
