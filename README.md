# Data Engineering: Storing Big Data Predict 

© Explore Data Science Academy

## Overview 

After much hard work, dedicated studying, and exercising of your practical knowledge, you finally find yourself in your first job as a data engineer- Congratulations ⭐️! 

Your boss, who’s a senior DE, is excited to have you join the team. However, seeing that you’re brand new, she’s a little cautious of your capabilities... As such, she decides to test out your skills by giving you two tasks based on work that your team has recently performed. Eager to prove your mettle to your boss and the greater team, you readily accept the challenge 🥋!

Within the sections below, we provide links to the instructions, resources, and assessments associated with each task: 

##  Part-1: On-premise Source Connection
### Instructions 🧑‍🏫

A detailed set of instructions guiding you through several steps of your boss's first task can be found [here](part_1_overview.md).

### Resources 📕

The resources below are provided in order to help complete this task: 

**Code**: 
 - [Linux instance CloudFormation YAML template](code/part1/student_linux_template.yml)

**Learning Material**: 
 - [Getting Started with YAML](https://www.cloudbees.com/blog/yaml-tutorial-everything-you-need-get-started/)
 - [Using YAML for CloudFormation](https://markrichman.com/yaml-for-aws-cloudformation/)
 - [CloudFormation Concepts](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/cfn-whatis-concepts.html)
 - [A Beginner's Guide to CloudFormation Templates](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/gettingstarted.templatebasics.html)
 - [CloudFormation Template Anatomy](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/template-anatomy.html)
 - [Resource Dependence in CloudFormation Resource Creation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-attribute-dependson.html)
 - [Validate a CloudFormation Template via the AWS CLI](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-validate-template.html)

### Assessments ⏱

The following actions need to be taken in order to complete the assessments used within the first task for the predict: 
 - [ ] **Submit CloudFormation templates**
 - [ ] **Generate AWS File Gateway-based SNS alert email** 
 - [ ] **Complete Task 1 MCQ**



##  Part-2: Streaming Data Pipeline
### Instructions 🧑‍🏫

A set of high-level instructions surrounding your boss's second task can be found [here](part_2_overview.md).

### Resources 📕

The resources below are provided in order to help complete this task: 

**Code**: 
 - [Streaming lambda script](code/part2/student_streaming_lambda.py)
 - [Custom SNS notification lambda script](code/part2/lambda_sns_notification.py)

### Assessments ⏱

The following actions need to be taken in order to complete the assessments used within the second task for the predict: 
 - [ ] **Stream ~5min of synthetic data through your data pipeline into your S3 bucket** 
 - [ ] **Generate custom pipeline failure SNS alert email** 
 - [ ] **Complete Task 2 MCQ**  


## Athena Upload
You need to upload a zip folder to Athena.   
Here is what is expected inside of the zip folder uploaded by a student named Dora Explorer.    
1. Dora-Explorer-VPC.yml   
2. Dora-Explorer-Windows-Instance.yml   
3. Dora-Explorer-Architecture-Diagram.png   
4. Dora-Explorer.csv (see below for example)  

| Name | Surname | File Gateway S3 Bucket Name | Fileshare Alert SNS Topic ARN | Delivery Stream S3 Bucket Name | Streaming SNS Topic ARN |
|--- |--- |--- |--- |--- |--- |
| Dora | Explorer | dedoraexplorer-source-file-gateway | arn:aws:sns:region:123456789:DEDOREXP-Fileshare-transfer-alert | dedoraexplorer-deliverystream-s3 | arn:aws:sns:region:123456789:DEDOREXP-streaming-sns-topic |

## FAQ ❓

This section of the repo will be periodically updated to represent common questions which may arise around its use. If you detect any problems/bugs, please [create an issue](https://help.github.com/en/github/managing-your-work-on-github/creating-an-issue) and we will do our best to resolve it as quickly as possible.

We wish you all the best in your learning experience 🚀!

<p align='center'>
     <img src="figs/EDSA_logo.png"
     alt='EDSA-logo'
     width=450px/>
     <br>
</p>
