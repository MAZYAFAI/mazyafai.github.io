+++
title = 'Banking and Financial'
date = 2022-02-02
PublishDate = 2022-05-5
draft = true
+++

This DevOps project is based on a real time DevOps project implemented in Banking and
Finance domain.
◦  Goal of Devops Project is to deploy the website on nginx on AWS using terraform, gitlab,
nginx, docker and using GitHub CI CD tool for Devops pipeline and Orchestration tool
Kubernetes.
◦  We will create an IAAC (Infrastructure as a code) with the help of CICD for devops pipeline
◦  Terraform will use AWS s3 as it’s backend to keep the state of terraform. The script
setup_pipeline_state.sh will first check if the s3 bucket already exists, if it exists it will fetch the
terraform state.
◦  it will create a new bucket with name starting with dev-app-tf-state. We will deploy the
website on your EC2 machines with stages such as DEV, TEST, ACCEPTANCE, PRODUCTION.
