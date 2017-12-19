# awsome-aws
- 好棒棒 AWS 資源
- Collect some projects for Amazom web services, ~~except official resource~~.
- Too many star projects, I need another project to record these star projects. XD

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
- [小信豬的原始部落](https://godleon.github.io/)
- [Rammus](https://rammusxu.github.io/)
- [Thinking, Coding, and Learning.](https://rickhw.github.io/)
- [超猴崽工作日誌](http://g23988.blogspot.tw/)
- [台灣的Web工程師](https://tags.pixnet.net/blog/user/akuma1/AWS)
- [Complete Think](https://rickhw.github.io/)

## EC2
- [aws-spot-bot](https://github.com/Jakobovski/aws-spot-bot)
    - Tool for finding and launching the cheapest and most reliable AWS spot instances. 
- [kubernetes-ec2-autoscaler](kubernetes-ec2-autoscaler)
    - A batch-optimized scaling manager for Kubernetes
- [aws-ec2-ssh](https://github.com/widdix/aws-ec2-ssh)
    - Manage AWS EC2 SSH access with IAM
- [elastic-load-balancing-tools](https://github.com/aws/elastic-load-balancing-tools)
    - Classic load balancer to Application load balancer copy utility
    - 協助遷移 load balancer .   
- [beeswithmachineguns](https://github.com/newsapps/beeswithmachineguns)
    - A utility for arming (creating) many bees (micro EC2 instances) to attack (load test) targets (web applications). http://apps.chicagotribune.com/
    - 小蜜蜂機關槍 XD,  benchmark 的.
    - [New Network Load Balancer – Effortless Scaling to Millions of Requests per Second](https://aws.amazon.com/tw/blogs/aws/new-network-load-balancer-effortless-scaling-to-millions-of-requests-per-second/)
    - [Benchmarking with Bees with Machine Guns](http://blog.samstefan.co.uk/load-testing-with-bees-with-machine-guns/)
    - [手把手教你快速部署流量压测工具 – Bees with Machine Guns](https://aws.amazon.com/cn/blogs/china/bees-with-machine-guns/)
    - 因為 Siege, JMeter 這些工具都是從同一個 IP 位址發送請求, 無法很真實的模擬實際狀況.      
    
## RDS
- [fluent-plugin-rds-slowlog](https://github.com/kenjiskywalker/fluent-plugin-rds-slowlog)
    - Working with MySQL Database Log Files / aws documentation
    - (shinsaka/fluent-plugin-rds-log)[https://github.com/shinsaka/fluent-plugin-rds-log]
        - Amazon Web Services RDS(MySQL) general_log and slow_log input plugin.
- [ottertune](https://github.com/cmu-db/ottertune)
    - The automatic DBMS configuration tool
    - [Tuning Your DBMS Automatically with Machine Learning](https://aws.amazon.com/tw/blogs/ai/tuning-your-dbms-automatically-with-machine-learning/)
    - [Automatic Database Management System Tuning Through Large-scale Machine Learning](http://www.pdl.cmu.edu/PDL-FTP/Database/parameters.pdf)
    - 用機器學習優化資料庫, 酷!!
    
## DynamoDB
- [dynamic-dynamodb](https://github.com/sebdah/dynamic-dynamodb)
    - Dynamic DynamoDB provides auto scaling for AWS DynamoDB http://dynamic-dynamodb.readthedocs.org/
    - 姊夫爸專文介紹 [Auto Scale DynamoDB With Dynamic DynamoDB](https://aws.amazon.com/tw/blogs/aws/auto-scale-dynamodb-with-dynamic-dynamodb/)
        - BUT ==> Update (2017): DynamoDB now supports auto scaling out of the box! Check out my [new blog post](https://aws.amazon.com/blogs/aws/new-auto-scaling-for-amazon-dynamodb/) or read the [new documentation](http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/AutoScaling.html).
- [Local Amazon DynamoDB - tools, dump/restore and testing](http://serebrov.github.io/html/2015-02-01-dynamodb-local.html)
- [AWS-DynamoDB-to-MongoDB](https://github.com/JasonGhent/AWS-DynamoDB-to-MongoDB)
- [dynamo-archive](https://github.com/yegor256/dynamo-archive) Archive and Restore DynamoDB Tables, from Command Line
- [DynamoDBtoCSV](https://github.com/edasque/DynamoDBtoCSV) Dump DynamoDB data into a CSV file
- [dynamodb_utils](https://github.com/adamchainz/dynamodb_utils) A toolchain for Amazon's DynamoDB to make common operations (backup, restore backups) easier.
- [dynamodump](https://github.com/bchew/dynamodump) Simple backup and restore for Amazon DynamoDB using boto

## MongoDB
- [quickstart-mongodb](https://github.com/aws-quickstart/quickstart-mongodb)
    - [MongoDB on the AWS Cloud](http://docs.aws.amazon.com/quickstart/latest/mongodb/welcome.html)
    - https://d0.awsstatic.com/whitepapers/AWS_NoSQL_MongoDB.pdf
    - 這樣會比 DynamoDB 好用嗎？

## Elasticache
- [phpmemcacheadmin](https://github.com/elijaa/phpmemcacheadmin) 
    - Memcached server admin in php for monitoring and debugging
- [redis-rdb-tools](https://github.com/sripathikrishnan/redis-rdb-tools)
    - Parse Redis dump.rdb files, Analyze Memory, and Export Data to JSON
    - [From 1.5 GB to 50 MB: The Story of my Redis Database](https://davidcel.is/posts/the-story-of-my-redis-database/)
- [redis-stat](https://github.com/junegunn/redis-stat)
    - A real-time Redis monitoring tool

## Lambda
- [earn-aws-lambda](https://github.com/dwyl/learn-aws-lambda)
    - Learn how to use AWS Lambda to easily create infinitely scalable web services
    - 不錯的 lambda 
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
- [aws-lambda-scala-example-project](https://github.com/snowplow/aws-lambda-scala-example-project)
    - An AWS Lambda function in Scala reading events from Amazon Kinesis and writing event counts to DynamoDB http://snowplowanalytics.com
- [lambda-config-demo](https://github.com/theburningmonk/lambda-config-demo)
    - Demo of approaches to config management for AWS Lambda   
- [aws-lambda-power-tuning](https://github.com/alexcasalboni/aws-lambda-power-tuning)
    - Step Functions state machine generator for AWS Lambda Power Tuning
- [aws-lambda-cheatsheet](https://github.com/srcecde/aws-lambda-cheatsheet)
    - Lambda cheatsheet.

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
- [aws-s3-virusscan](https://github.com/widdix/aws-s3-virusscan)
    - Free Antivirus for S3 Buckets 
- [JetS3t](https://bitbucket.org/jmurty/jets3t/wiki/Home)
    - An open source Java toolkit for Amazon S3, Amazon CloudFront, and Google Storage Service
    - [http://jets3t.s3.amazonaws.com/index.html](http://jets3t.s3.amazonaws.com/index.html)
    - [http://www.jets3t.org/](http://www.jets3t.org/)
- [S3 Browser](http://s3browser.com/)
- [s3-pit-restore](https://github.com/madisoft/s3-pit-restore)
    - https://labs.madisoft.it/amazon-s3-point-in-time-restore/
    - A point in time restore tool for Amazon S3.    
- [S3 bucket enumerator](https://github.com/bbb31/slurp)
    - 嘿 嘿 嘿

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
- [cloudviz](https://github.com/mbabineau/cloudviz)
    - Makes nice graphs of Amazon CloudWatch data using Google Chart Tools
- [cloudgrapher](https://github.com/dmgress/cloudgrapher)
    - One page visualization tool for AWS CloudFormation scripts http://dmgress.github.io/cloudgrapher/
- [cloudwatch-elk](https://github.com/gilt/cloudwatch-elk)
    - AWS CloudWatch Logs to ELK

## Cloudformation
- [startup-kit-templates](https://github.com/awslabs/startup-kit-templates)
    - CloudFormation templates for setting up a startup's well-architected infrastructure on AWS. 
- [aws-cf-templates](https://github.com/widdix/aws-cf-templates)
    - Free Templates for AWS CloudFormation

## DMS
- [ptolemy](https://github.com/cloudreach/ptolemy)
    - Write terse AWS DMS table mappings.

## CloudTrail
- [aws_configurer](https://github.com/KKBOX/aws_configurer)
    - Configure AWS accounts for CloudTrail, Root Account Usage Monitor.
    - 雖然已搞定還是記上一筆ㄡ一筆
- [CloudTrailViewer](https://github.com/githublemming/CloudTrailViewer)
    - Java desktop tool for viewing AWS CloudTrail log files
    - cloudtrail 的 log, 要如何找呢?

## Kinesis
- [kinesalite](https://github.com/mhart/kinesalite)
    - An implementation of Amazon's Kinesis built on LevelDB
    - [LevelDB](http://leveldb.org/), https://github.com/google/leveldb, https://zh.wikipedia.org/wiki/LevelDB

## Batch
- [SampleBatchProcessing](https://github.com/danilop/SampleBatchProcessing)
    - Sample Implementation of Batch Processing on Amazon Web Services (AWS)
    - [Samplebatchprocessing](http://danilop.github.io/SampleBatchProcessing/)

## PHD, Personal Health Dashboard
- [aws-health-tools](https://github.com/aws/aws-health-tools)
    - The samples provided in AWS Health Tools can help users to build automation and customized alerting in response to AWS Health events.
    - PHD 的東西原只能在登入 console 時才能看得到, 有點被動.
    - Customized alerts in response to AWS Health events.
    - [AWS status: The complete guide to monitoring status on the web’s largest cloud provider](http://blog.statuspage.io/aws-status-the-complete-guide-to-monitoring-status-on-the-web-s-largest-cloud-provider)
        - 有時 AWS 的 status page 也不牢靠, 怎辦勒??!! 試試這個作者的一些建議       
    - [AWS release aws-health-tool for Personal Health Dashboard (PHD)](https://blog.hothero.org/2017/03/08/aws-release-aws-health-tool-for-personal-health-dashboard-phd/)
    - [AWS outage? Datadog alerts you](https://www.datadoghq.com/blog/aws-outage-datadog-alerts-you/)
        - DataDog 的作法, 雖然沒在用 DataDog.
- [Monitoring AWS Health Events with Amazon CloudWatch Events](https://docs.aws.amazon.com/health/latest/ug/cloudwatch-events-health.html)

## Trusted Advisor
- [Trusted-Advisor-Tools](https://github.com/aws/Trusted-Advisor-Tools)
    - The sample functions provided help to automate AWS Trusted Advisor best practices using Amazon Cloudwatch events and AWS Lambda.
    
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
- [awspec](https://github.com/k1LoW/awspec)
    - RSpec tests for your AWS resources.
- [AWSCloudLab](https://github.com/wongcyrus/AWSCloudLab)
    - AWS Cloud Lab is aims to facilitate educators using AWS in their teaching.
    
## Security
- [git-secrets](https://github.com/awslabs/git-secrets)
    - aws 祕密武器
    - [AWS 會在 INTERNET 上掃 CREDENTIALS](https://shazi.info/aws-%E6%9C%83%E5%9C%A8-internet-%E4%B8%8A%E6%8E%83-credentials/)

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
- [Jayendra's Blog](http://jayendrapatil.com/)
    - 蠻多人推薦的神筆記
- [CDA_resource](https://github.com/g23988/CDA_resource)    
    - 有一些 sampel question
- [AWS Solutions Architect](http://aws.tuongminh.pro/associate)
    - mock test
    
## Deep Learning
- [GoDeeper](https://github.com/Miej/GoDeeper)
    - AWS p2.xlarge GPU optimized deep learning cluster-grenade.
- [deeplearning-cfn](https://github.com/awslabs/deeplearning-cfn)
    - CFN cluster for DeepLearning AMIs.
- [ecs-deep-learning-workshop](https://github.com/awslabs/ecs-deep-learning-workshop)
    - Material for re:Invent 2016 - CON314 - Workshop: Deploy a Deep Learning Framework on Amazon ECS 
    
## practice exam
