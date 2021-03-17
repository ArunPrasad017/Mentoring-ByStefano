Mentoring-Arun
=====================

:Author: Stefano Gallotti
:Version: 1.0
:Date Initiated: 2019-09-23

.. contents:: Table of Contents

2020-04-07 - Agenda
---------------------------
| # Sync on Covid situation

2020-03-09 - Agenda
---------------------------
| # Test Framework

2020-03-04 - Agenda
---------------------------
| # Python Streaming with Kafka

2020-02-24 - Agenda
---------------------------
| # Circle CI config

2020-02-17 - Agenda
---------------------------
| # Sample project:
| - Defined Roadmap with Practical and Theoretical paths

2020-02-10 - Agenda
---------------------------
| # Personal Improvement discussion
| - Decided to focus on OOP and Python coding implementing a sample project

2020-01-27 - Discussed points
---------------------------
| # Personal Improvement
| - Where to go next? -- 1st week (give a summary regarding journey)
| # Python
| - Test functionalities - unit (Interest - 4, completeness - 1)
| - Concentrate on Improving coding skills - (Interest - 5, completeness - 3) 
| - Best practices - (Interest - 5, completeness - 2)
| - Design patterns - (OOP) (Interest - 4, completeness - 1)
| # SQL - DWH patterns - (Interest - 4, completeness - 1)
| - Theoretical aspects
  + a) how to design warehousing?
  + b) How to do perform Querying?
  + c) Focus on improving query performance
| - Practical aspects (Interest - 2, completeness - 1)
  + Technology - SQL server vs Hadoop( differences in technicality to be discussed)
| - High level design of application/system - (Interest - 4, completeness - 1)
| # Tools 
| - Mastering the tools or identifying the right tools to improve productivity -- (Interest - 5, completeness - 3)
| - Project Mgmt skills

| - Ensure the flask project is working E2E so as to improve on points mentioned above 
| - Use 100 days of code as a section of flask project

2019-12-09 - Agenda
---------------------------
| EoY reviews conversation.
| Summary of mentoring activities so far.

2019-12-02 - Agenda
---------------------------
| Completion of Jenkins/Terraform pipeline with successful deployment.
| Debugging of issues with Jenkins.


2019-11-25 - Agenda
---------------------------
| Airflow on kubernetes
| https://github.expedia.biz/Egencia/hip
| https://confluence.expedia.biz/display/ECT/Getting+Started+with+kubectl
| https://kubernetes.io/docs/tasks/tools/install-kubectl/
| `https://expedia.slack.com/files/U861A5EHG/FRGBZSFL5/airflow-presentation.pptx` to pont to the right file location

2020-01-27 - Discussed points
---------------------------
| # Personal Improvement
| - Where to go next? -- 1st week (give a summary regarding journey) 
| # Python 
| - Test functionalities - unit
| - Concentrate on Improving coding skills - 
| - Best practices
| - Design patterns
| # SQL - DWH patterns
| - Theoretical aspects 
  + a) how to design warehousing?
  + b) How to do perform Querying?
  + c) Focus on improving query performance
| - Practical aspects 
  + Technology - SQL server vs Hadoop( differences in technicality to be discussed)
| # Tools
| - Mastering the tools or identifying the right tools to improve productivity
| - Project Mgmt skills

2019-12-09 - Agenda
---------------------------
| EoY reviews conversation.
| Summary of mentoring activities so far.

2019-12-02 - Agenda
---------------------------
| Completion of Jenkins/Terraform pipeline with successful deployment.
| Debugging of issues with Jenkins.


2019-11-25 - Agenda
---------------------------
| Airflow on kubernetes
| https://github.expedia.biz/Egencia/hip
| https://confluence.expedia.biz/display/ECT/Getting+Started+with+kubectl
| https://kubernetes.io/docs/tasks/tools/install-kubectl/
| `https://expedia.slack.com/files/U861A5EHG/FRGBZSFL5/airflow-presentation.pptx` to pont to the right file location

2019-11-18 - Agenda
---------------------------
| # CI/CD
| - first terraform example with jenkins.
| - open point about need for resources inside the jenkins script.
| - should terraform take care of all the objects and leave to jenkins just the trigger?
| - configure for having multiple envs (lab/prod)


2019-11-11 - Agenda
---------------------------
| # CI/CD


2019-11-04 - Agenda
---------------------------
| # CI/CD
| - create a KUMO template for Terraform
| - https://gcobuild-jenkins.sb.karmalab.net:8443/job/arun-terraform-deploy/
| - get write access to Egencia Jenkins
| - try calling terraform image in the Jenkins

2019-10-28 - Agenda
---------------------------
| # CI/CD
| - create a KUMO template for Terraform

2019-10-21 - Agenda
---------------------------
| # CI/CD
| Kumo / Travis CI
| Tasks:
| - explore if we can build a Kumo pipeline for Terraform.
| - Jenkins to execute Terraform scripts against aws.
| Side Project 2 - https://github.com/ArunPrasad017/apa-docker-react
- This side project is to develop a docker container and create a mock CICD process using TravisCI and AWS ElastiBeanStalk
- This involved creating a docker file for dev and for prod equivalent environment.
- The docker file inherently uses two base images here
  + a) node alpine
  + b) nginx
- The Travis CI configured to view the git hub repo mentioned above(This can be done manually via logging into travisci.org and adding the github repo link)
- AWS ElastiBeanStalk configured to scale and run the docker images as per increase in load
|
2019-10-15 - Agenda
---------------------------
| # docker compose
| Faust

| Github project repo for docker - https://github.com/ArunPrasad017/docker-playground.git
| Discussed regarding the usage of docker to run Pyunit tests
| Side project 1 - https://github.com/ArunPrasad017/docker-playground/tree/master/visits
- Side project is the visits project which keeps a count of the number of times a webpage is visited
- Have a Dockerfile with the basic node js base image and run npm start
- Using a docker-compose config to have redis service and node service.
- Helped learn how to use docker file and docker-compose files
|

2019-10-07 - Agenda
---------------------------
| # docker for spark and testing
| - https://github.expedia.biz/ECP/dci-data-dci-docker
  docker run -it --rm -w /tests -v $(pwd):/tests 081465268627.dkr.ecr.us-west-2.amazonaws.com/dci-pyspark /bin/bash
  usually pwd is my git repo folder ( or alternatively my github folder only if I need more than one project)

| more on unit test/integration test and how to apply them to snowflake etl logic
|
| sample project
- https://github.expedia.biz/ECP/dci-data-sample
|
| # more comple project
- https://github.expedia.biz/ECP/dci-data-action ( search start with dci-data-)
- https://github.expedia.biz/ECP/dci-data-forecast ( more recent one with view test, integration tests )
|
| # about docker:
https://medium.com/@stefanogallotti/the-benefits-of-docker-for-development-7ac3e3504f7b
|
2019-09-30 - Agenda
---------------------------
| To Be Discussed:
| Python, Data Structures and how they are used in Projects

 - Faust - http://fauststream.com/en/latest/
 - https://github.expedia.biz/ECP/di-kafka-presence-processor
 - AsyncIO
 - PySpark and Dataframe
 Podcasts:
  - https://talkpython.fm/
  - https://pythonbytes.fm/
  - https://www.dataengineeringpodcast.com/
  - https://www.redhat.com/en/command-line-heroes
|
2019-09-23 - Agenda
---------------------------
- Logistics 30 mins Monday afternoon.
- Expectations
  - enhance knowledge about BI and data science and M/L
- Others
- CI/CD (Kumo)
- Streaming (Kafka) Faust
- Python
 - Language
 - PySpark
 - Testing
- Containers
- Airflow for ETL both SEA and expeso
- Terraform
- Tooling
|
TODO
---------------------------
- order subject by priority
- Structure for major subjects in the repo
