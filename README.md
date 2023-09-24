# DatennaTechincalAssesment
Datenna - Technical Assessment


1. Create a Helm Chart Directory

helm create my-flask-app
cd my-flask-app


2. Define Helm Chart Templates

Inside the chart directory, you'll find a templates directory where you define the Kubernetes resource templates. You can create a Deployment and a Service resource for your Flask application.

3.  Configure Helm Chart Values

Create a values.yaml file in the chart directory to define configuration values for your application. You can specify values such as the image repository, tag, and replica count