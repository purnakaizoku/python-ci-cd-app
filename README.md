# python-ci-cd-app
# Spcl infotech Sevices PVT LTD assenment

# Prerequisites
Jenkins (with the necessary plugins)
*Git plugin
* plugin
*Pipeline plugin
Docker: For building and pushing Docker images.
GitHub account: For the repository and storing the application code.
Docker Hub account: For storing the Docker images.
Python (Python 3.x): To run the application and install dependencies.
# step by step environment
abouve git repo and files 
create a new job python-cicd-app in jenkins
manage creditioals like dockerhub user pass and git

# Configure Docker Hub Credentials in Jenkins
In Jenkins, go to Manage Jenkins → Manage Credentials and add your Docker Hub credentials. Use this credentials ID in the Jenkins pipeline to authenticate and push Docker images.

# Install Dependencies and Build Docker Image

necessary dependencies in the requirements.txt file 
The Dockerfile builds the Docker image for the Python application.
# Running the Pipeline
Once Jenkins is set up with the pipeline script and credentials, trigger the pipeline manually or automatically with every commit to the GitHub repository.
Jenkins will:
Clone the repository.
Install the Python dependencies.
Build the Docker image.
Push the image to Docker Hub.

# Access the Docker Image
then acces the image # docker pull purna6/python-ci-cd-app

# conclusion
This setup automates the process of building, testing, and deploying a Python application using Jenkins and Docker. The pipeline ensures that every change pushed to GitHub is automatically built, tested, and deployed to Docker Hub, improving efficiency and reliability.

# Access the Application in Your Browser
http://44.244.199.228:8080
You should see the Flask app displaying "Hello, World!" in your web browser.
