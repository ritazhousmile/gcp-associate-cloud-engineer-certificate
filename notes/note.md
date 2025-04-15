
# **Associate google cloud engineer certificate study notes:**

## **role of associate cloud engineer:**

- Deploys and secures applications and infrastructure, monitors operations of multiple projects, and maintains enterprise solutions to ensure that they meet target performance metrics. 
- working with public clouds and on-premise solutions.
- able to use google cloud console and the command-line interface to perform command platform-based tasks to maintain and scale one or more deployed solutions that leverage google-managed or self-managed services on google cloud

## *COURSES**

The courses recommended for the Associate Cloud Engineer certification include:
- Google Cloud Fundamentals: Core Infrastructure, Architecting with Google Compute Engine, and Getting Started with Google Kubernetes Engine.

## *setting up cloud environment*

- establishing a resource hierarchy
    - How to set up a resource hierarchy on Google Cloud depends on the needs and structure of the organization.
    ![alt text](image.png)
- implementing organizational policies
- managing projects and quotas
- managing users and groups
    - how to manage Cymbal Superstore’s users and groups in Cloud Identity, a service for managing users and groups if you are not doing so via Google Workspace.
- applying access management.
- Setting up billing and monitoring the use of your cloud resources
    - different departments associated with each application will be responsible for compute and storage costs. You’ll need to create a different billing account for each group and link each project to the appropriate account. You’ll need to set up custom billing budgets and alerts for this department. Each department will also need you to set up billing exports that can be used to track charges.
- granting members IAM roles 
    - Managing permissions and rules at a group level is easier than keeping track of permissions for individual users.
        - bigquery.dataViewer role
        - bigquery.jobs.create permission.
- Google Cloud Observability, which used to be called Google Cloud’s operations suite and Stackdriver before that, provides metrics and logging services for all of your services, resources, and projects in your cloud architecture. To monitor metrics from multiple projects, you set up project scoping. If Cymbal Superstore’s Operations department decides to monitor metrics across all three supply chain projects in the staging environment project, you will set staging as a scoping project and then add dev and production as monitored projects.
