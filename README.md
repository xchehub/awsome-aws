# awsome-aws
- 好棒棒 AWS 資源
- Collect some projects for Amazom web services, except official resource.
- Too many start projects, I need another project to record these star projects. XD

## Web site
- [https://www.kilait.com/](https://www.kilait.com/)
- [clifflu 又架 blog 了 O.o/](https://blog.clifflu.net/)
- [第二十四個夏天後](http://blog.changyy.org/)
- [Mr. 沙先生](https://shazi.info/)
- [JYEH'S BLOG](http://jyeh-blog.logdown.com/)
- [World is Interesting](http://newtomaso.blogspot.tw/)
- [Jex’s Note](http://blog.jex.tw/)
- [AWS那些事](http://www.aws-faq.com/)
- [awsok](http://www.awsok.com/) <<< 東摳摳西摳摳
- [Idan Bean 種豆得瓜](http://idanbean.idanbird.net/)
- [AWS經驗教學 - 台灣的Web工程師](http://akuma1.pixnet.net/blog/category/11469946)

## EC2
- [aws-spot-bot](https://github.com/Jakobovski/aws-spot-bot)
    - Tool for finding and launching the cheapest and most reliable AWS spot instances. 
- [kubernetes-ec2-autoscaler](kubernetes-ec2-autoscaler)
    - A batch-optimized scaling manager for Kubernetes
    
## RDS
- [fluent-plugin-rds-slowlog](https://github.com/kenjiskywalker/fluent-plugin-rds-slowlog)
    - Working with MySQL Database Log Files / aws documentation
    - (shinsaka/fluent-plugin-rds-log)[https://github.com/shinsaka/fluent-plugin-rds-log]
        - Amazon Web Services RDS(MySQL) general_log and slow_log input plugin.
        
## Elasticache
- [phpmemcacheadmin](https://github.com/elijaa/phpmemcacheadmin) 
     - Memcached server admin in php for monitoring and debugging

## Lambda
- [lambda-packs](https://github.com/ryfeus/lambda-packs)
    - pack Tensorflow in to a Lambda.
    - https://github.com/ryfeus/lambda-packs/tree/master/Pyrestest_wrk
        - https://www.reddit.com/r/aws/comments/6142fy/load_testing_using_aws_lambda/
        - load testing with WRK and pyresttest.
            - https://github.com/wg/wrk
            - https://github.com/svanoort/pyresttest
        - [bench-rest](https://github.com/jeffbski/bench-rest)
    
- [python-lambda](https://github.com/nficano/python-lambda)
    - A toolkit for developing and deploying serverless Python code in AWS Lambda.
- [serverless-chrome](https://github.com/adieuadieu/serverless-chrome)    
    - Run headless Chrome on AWS Lambda
    - Provide the scaffolding for using Headless Chrome during a serverless function invocation. 
    - 這樣 Lambda 可跑 Chrome 螢幕截取或 print PDF了
- [lambda-refarch-imagerecognition](https://github.com/awslabs/lambda-refarch-imagerecognition)    
    - Image Recognition and Processing Backend reference architecture.
    - Using AWS Lambda, Amazon S3, Amazon DynamoDB and Amazon Rekognition.
- [learn-aws-lambda](https://github.com/dwyl/learn-aws-lambda)
    - Learn how to use AWS Lambda to easily create infinitely scalable web services
- [LambStatus](https://github.com/ks888/LambStatus)
    - Serverless Status Page System
- [/lambda-machine-local](https://github.com/lambda-linux/lambda-machine-local)
    - Stable and secure local docker development environment for AWS Users https://lambda-linux.io/
    - It provides a stable and secure local docker development environment.
- [lambda-packages](https://github.com/Miserlou/lambda-packages)
    - Various popular python libraries, pre-compiled to be compatible with AWS Lambda
    - https://blog.zappa.io/
    - 想上次找 mysql package, 原先在用的 MySQLdb trouble, 後來改用 PyMySQL.
    - [Problems using MySQL with AWS Lambda in Python](https://stackoverflow.com/questions/35763380/problems-using-mysql-with-aws-lambda-in-python)
- [docker-lambda](https://github.com/lambci/docker-lambda)
    - Docker images and test runners that replicate the live AWS Lambda environment
    - 要怎樣在 local , debug Lambda 呢？ 試試用 docker.
- [lambci](https://github.com/lambci/lambci)
    - A continuous integration system built on AWS Lambda
    - [Introducing LambCI — a serverless build system](https://medium.com/@hichaelmart/lambci-4c3e29d6599b)

## S3
- [setup-ipsec-vpn](https://github.com/hwdsl2/setup-ipsec-vpn)
    - Scripts to build your own IPsec VPN server, with IPsec/L2TP and Cisco IPsec on Ubuntu, Debian and CentOS
- [s3-lambda](https://github.com/littlstar/s3-lambda)    
    - Lambda functions over S3 objects with concurrency control (forEach, map, reduce, filter) 
- [DragonDisk](http://www.s3-client.com/)
    - File manager for Amazon S3
- [Amazon S3 Tools](http://s3tools.org/s3cmd)
    - S3cmd : Command Line S3 Client and Backup for Linux and Mac
- [vue-s3-dropzone](https://github.com/kfei/vue-s3-dropzone)
    - Vue.js component works with AWS S3 serverlessly
    - 用 AWs Lambda 實現的 S3 uploader

## Redshift
- [redshift-r](https://github.com/pingles/redshift-r)
    - Small R package for accessing Redshift 
    
## ECS
- [ecs-watchbot](https://github.com/mapbox/ecs-watchbot)
    - Library to help run a highly-scalable AWS service.
- [ecs-cfn-refarch](https://github.com/pahud/ecs-cfn-refarch)
    - Amazon ECS reference architecture
    - 先收下, XD.
    - 在AWS使用ECS Windows container. 一鍵自動生成 ECS Windows Container 環境，利用 Lambda+custom resource 查詢最新的 AMI ID 帶給ASG+LC  起 Spot instance 註冊到 ECS Cluste 然後起 ECS Service 掛上ALB.
- [ecs-host-service-scale](https://github.com/miketheman/ecs-host-service-scale)
    - Extending ECS Auto-scaling for under $2/month with Lambda
    - http://www.miketheman.net/2017/01/09/extending-ecs-auto-scaling-for-under-2month-with-lambda/

## CLI
- [awless](https://github.com/wallix/awless)
    - The Mighty CLI for AWS

## Cloudwatch
- [awslogs](https://github.com/jorgebastida/awslogs)
    - AWS CloudWatch logs for Humans.
- [cloudwatch-logs-subscription-consumer](https://github.com/awslabs/cloudwatch-logs-subscription-consumer)
    - A specialized Amazon Kinesis stream reader. 
    - Help you deliver data from Amazon CloudWatch Logs to any other system in near real-time using a CloudWatch Logs Subscription Filter.
- [axibase-collector - AWS job](https://github.com/axibase/axibase-collector/blob/master/jobs/aws.md)
    - Collect data from the Amazon Web Services CloudWatch service and store it in the Axibase Time Series Database for long-term retention, reporting, and analytics.
- [cloudwatch-librato](https://github.com/mapbox/cloudwatch-librato)
    - Fetch AWS CloudWatch metrics and submit to Librato Metrics

## Cloudformation
- [startup-kit-templates](https://github.com/awslabs/startup-kit-templates)
    - CloudFormation templates for setting up a startup's well-architected infrastructure on AWS. 

## DMS
- [ptolemy](https://github.com/cloudreach/ptolemy)
    - Write terse AWS DMS table mappings.

## CloudTrail
- [aws_configurer](https://github.com/KKBOX/aws_configurer)
    - Configure AWS accounts for CloudTrail, Root Account Usage Monitor.
    - 雖然已搞定還是記上一筆ㄡ一筆

## Kinesis
- [kinesalite](https://github.com/mhart/kinesalite)
    - An implementation of Amazon's Kinesis built on LevelDB
    - [LevelDB](http://leveldb.org/), https://github.com/google/leveldb, https://zh.wikipedia.org/wiki/LevelDB

## Management/Monitor Tool
- [AWS Usage Tool](https://github.com/Netflix/ice)
    - Ice provides a birds-eye view of our large and complex cloud landscape from a usage and cost perspective.
- [Botmetric](https://www.botmetric.com/)
    - Integrated AWS Cloud Management Platform
- [skew](https://github.com/scopely-devops/skew)
    - A package for identifying and enumerating cloud resources.
    - Ref. [How to programmatically list all aws resources and tags](http://stackoverflow.com/questions/30674938/how-to-programmatically-list-all-aws-resources-and-tags)
    
## Docs
- [og-aws](https://github.com/open-guides/og-aws)
    - Amazon Web Services — a practical guide

## Others
- [archon](https://github.com/kubeup/archon)
    - Open source tool for cluster creation and daily operations.
- [the cloudyr project](https://github.com/cloudyr)
    - Making R Cloudier!
    - https://cloudyr.github.io/  
    - 在 R code 裡 access aws resource. 會不會就是重新包裝了 aws cli
- [chrome-aws-api-debugger](https://github.com/zorrofox/chrome-aws-api-debugger)
    - AWS API debugger, 不知還行不行.
- [aws-sdk-mock](https://github.com/dwyl/aws-sdk-mock)
    - AWSomocks for Javascript/Node.js aws-sdk tested, documented & maintained. Contributions welcome!
- [amnigos/CloudWatch](https://github.com/amnigos/CloudWatch)
    - This is an initiative to create browser based measurement of Amazon EC2 latency for all different regions.
    -  aws 各 region 幾個 service 的

## awslabs
- [ecs-refarch-continuous-deployment](https://github.com/awslabs/ecs-refarch-continuous-deployment)
    - ECS Reference Architecture for creating a flexible and scalable deployment pipeline to Amazon ECS using AWS CodePipeline
- [ecs-refarch-service-discovery](https://github.com/awslabs/ecs-refarch-service-discovery)
    - An EC2 Container Service Reference Architecture for providing Service Discovery to containers using CloudWatch Events, Lambda and Route 53 private hosted zones. 
- [ecs-refarch-batch-processing](https://github.com/awslabs/ecs-refarch-batch-processing)
    - A reference architecture for handling batch processing workloads using Amazon ECS. 
- [ecs-refarch-cloudformation](https://github.com/awslabs/ecs-refarch-cloudformation)
    - A reference architecture for deploying containerized microservices with Amazon ECS and AWS CloudFormation (YAML) 
- [ecs-refarch-continuous-deployment](https://github.com/awslabs/ecs-refarch-continuous-deployment)
    - ECS Reference Architecture for creating a flexible and scalable deployment pipeline to Amazon ECS using AWS CodePipeline
- [eb-python-flask](https://github.com/awslabs/eb-python-flask)
    - Simple Python and Flask sample application from [AWS Elastic Beanstalk Developer Guide](http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create_deploy_Python_flask.html)
- [lambda-refarch-imagerecognition](https://github.com/awslabs/lambda-refarch-imagerecognition)
    - Image Recognition and Processing Backend reference architecture
- [lambda-refarch-fileprocessing](https://github.com/awslabs/lambda-refarch-fileprocessing)    
    - Serverless Reference Architecture for Real-time File Processing
    - [無伺服器參考架構：即時檔案處理](https://github.com/awslabs/lambda-refarch-fileprocessing/blob/master/README/README-TW.md)

# Alexa, 好像不錯玩
- [flask-ask](https://github.com/johnwheeler/flask-ask)
    - Alexa Skills Kit for Python

## Certification
- [AWSCurriculums](https://github.com/excellalabs/AWSCurriculums)
    - Curriculums for learning AWS, notably for the Developer or Solutions Architect certifications 


## Deep Learning
- [GoDeeper](https://github.com/Miej/GoDeeper)
    - AWS p2.xlarge GPU optimized deep learning cluster-grenade.
- [deeplearning-cfn](https://github.com/awslabs/deeplearning-cfn)
    - CFN cluster for DeepLearning AMIs.
- [ecs-deep-learning-workshop](https://github.com/awslabs/ecs-deep-learning-workshop)
    - Material for re:Invent 2016 - CON314 - Workshop: Deploy a Deep Learning Framework on Amazon ECS 
    
## practice exam
