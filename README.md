# medusa-project
This project automates the deployment of the medusa open source headless commerce backend using Terraform on AWS Fargate, a serverless container platform. 
It also integrates a continuous Deployment(CD) pipeline using GitHub actions to streamline updates.
The infrastructure includes an ECS cluster, Fargate service, RDS for postgreSQL, S3 for file storage and necessary networking(VPC,Subnets,Security groups).
The goal is to achieve a fully automated and scalable cloud native medusa backend deployment.
