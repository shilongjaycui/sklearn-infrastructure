# `sklearn-infrastructure`
This is the sample code of a [scikit-learn](https://scikit-learn.org/stable/) machine learning model that's
1. served by [FastAPI](https://fastapi.tiangolo.com/),
2. containerized with [Docker](https://www.docker.com/), and
3. deployed to [Amazon Web Services (AWS)](https://aws.amazon.com/) using [Terraform](https://www.terraform.io/).

## What motivated the creation of this project?
To enable data scientists and ML practitioner to focus on building models in production and not worry about model serving or model deployment.

## I'm in. How do I build models that are deployed to production from the start?
1. Clone this repository:
   ```
   $ git clone git@github.com:shilongjaycui/sklearn-infrastructure.git
   ```
2. Navigate into the repository:
   ```
   $ cd sklearn-infrastructure
   ```
3. [Create an AWS account](https://aws.amazon.com/resources/create-account/) if you don't have one already.
4. [Install AWS Command Line Interface (CLI)](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html); then, verify you have AWS CLI successfully installed on your local machine by running the following commands:
   ```
   $ which aws
   /usr/local/bin/aws
   $ aws --version
   aws-cli/2.15.30 Python/3.11.6 Darwin/23.3.0 botocore/2.4.5
   ```
5. Create an [IAM](https://aws.amazon.com/iam/) user with just enough permissions (see why [here](https://docs.aws.amazon.com/wellarchitected/latest/framework/sec_permissions_least_privileges.html)) to deploy Docker containers to [ECS](https://aws.amazon.com/ecs/):
   ```
   $
   ```
6. Configure the terminal session to use the newly-created IAM user:
   ```
   $
   ```
7. Deploy the machine learning model to AWS:
   ```
   $
   ```
8. Take a look at the deployed model: