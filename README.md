
## ND9991 - C3 - Build CI/CD Pipelines, Monitoring, and Logging

### You are in the green branch of the repository.

This repository provides the supporting material for the "ND9991 Cloud DevOps Nanodegree - C3 - Build CI/CD Pipelines, Monitoring, and Logging" course. This repo has two more branches, other than the master branch. 

* Blue/Green branch corresponds to the Blue/Green deployment strategy. Make sure that you checkout branches "blue" and "green" to see how blue/green deployment was performed in the course.
* You can create any more branches for a multiple pipeline set-up, as directed in the demonstration video. 

### Steps

1. Create a key-name called -> Jenkins_demo
2. Select the AZ (us-east-2) and copy/paste the SG for ELB and `update roles/create_instance/tasks/main.yaml` with the SG in group_id (Create EC2 instances)
3. Create Hosted Zone using wread.com (roles/route53/tasks/main.yaml)
