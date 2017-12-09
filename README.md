# credit-card-fraud-detection

ssh -i comp4651project.pem root@<DNS>
  
https:///<DNS>:8888/tree

S3 link: https://s3.console.aws.amazon.com/s3/buckets/creditfrauddata/?region=us-east-1&tab=overview

dataset link: https://www.kaggle.com/ntnu-testimon/paysim1

#### Getting Started
About the branches:
- ec2: for code that has been tested on ec2 instances
- sparkvm: for code that are run on sparkvm

The main difference between ec2 and sparkvm (so far) is only on how we are accessing the dataset. On "ec2", we read from the file stored in s3. On the other hand, "sparkvm" assumes the file is available in the following path "/vagrant/<filename>".
  
To start developing on the sparkvm in your local machine:
1. Clone this repo in the home directory of your sparkvm
2. Download the dataset and place it in /vagrant directory, which is the same directory as your sparkvm's Vagrantfile.

