# Jenkins Pipeline

This directory contains Jenkins pipeline.

### Prerequisites
* Add Baselime API key to credentials as `baselime-api-key`
* Add `Jenkinsfile` to root of your repository of your observability code repository

![img.png](img.png)

### Pipeline steps
1. Checkout the code
2. Show the changes to be applied
3. Ask for confirmation to continue
4. Apply changes
5. Produce alerts reports with the latest changes applied.