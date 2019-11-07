# Josh Campbell's Portfolio
Hello recruiter or hiring manager! My name's Josh and I like Python, Docker, Linux, AWS, Amazon Alexa, drones, and beer. This is a curated list of projects I have on GitHub and other places on the web that I think you might be interested in. My full GitHub profile can be found [here](https://github.com/irlrobot) and [this is my StackOverflow profile](https://stackoverflow.com/users/3066574/irlrobot) if you're into that sort of thing.

# Projects
## lambda-chef-node-cleanup - Python AWS Lambda Function
https://github.com/awslabs/lambda-chef-node-cleanup

This little project watches for AWS CloudWatch events for EC2 instance termination to automatically remove nodes from Chef Server saving $$$. It's meant to run as an AWS Lambda function.

## aws_lambda_sample_events_python - Python Library
https://github.com/awslabs/aws_lambda_sample_events_python || https://pypi.org/project/aws-lambda-sample-events/

I wrote this to help test Python functions running on [AWS Lambda](https://aws.amazon.com/lambda/).

## GARLC - Python AWS Lambda Function
https://github.com/awslabs/lambda-runcommand-configuration-management

I worked on this while at AWS and legal wouldn't let me call it GARLC, so I had to call it lambda-runcommand-configuration-management. This was a POC to do continuous configuration management delivery (new marketing buzzword?!?! what have I done...) and was actually pretty fun to work on. Basically it uses AWS RunCommand to execute Ansible (in local mode) on hosts without actually needing SSH access anywhere (needs IAM Role). Terraform included for setup and teardown. It even has a friggin' [theme song](https://github.com/awslabs/lambda-runcommand-configuration-management#theme-song).

## Dockerfiles
https://github.com/irlrobot/dockerfiles

My collection of Dockerfiles. Largley uninteresting, but these days I do tend to do development exclusively using Docker.

## alppb - Python CLI Tool
https://github.com/irlrobot/alppb || https://pypi.org/project/alppb/

The Amazon Linux Python Package Builder (alppb) builds Python packages using the same version of Amazon Linux that the AWS Lambda service uses. Using alppb helps guarantee that any PyPI package your AWS Lambda app depends on will run properly. This is largely a portfolio project as it's a pretty overkill solution. Nevertheless, it's a great little project that showcases my ability to work with Python and AWS.

## wings - Python CLI Tool
https://github.com/irlrobot/wings

(Kinda abandoned at this point though I want to revisit it again one day)...The goal of wings is to build and manage opinionated CI/CD toolchains for software projects using select AWS services with minimal configuration by the user. This means you take your existing source code, write a little bit of TOML, run wings, and get a full CI/CD pipeline using native AWS tools ([Code Suite services](https://aws.amazon.com/products/developer-tools/)) that cost next to nothing. Knowledge of the underlying services is not required. Spend more time coding and less time managing your CI/CD.

## whodis - Python Library
https://github.com/irlrobot/whodis || https://pypi.org/project/whodis/

Automatically detect the programming language(s) present in a source code directory. Useful as a library for other projects that want to do automatic configuration. I originally built this for, and intended to use it with, my [wings](https://github.com/irlrobot/portfolio#wings) project before I decided on a different configuration system.

## pydng - Python CLI Tool and Library
https://github.com/irlrobot/pydng || https://pypi.org/project/pydng/

The Python Docker Name Generator (pydng) is a port of the Docker name generator written in Go. Just because...

# Alexa Skills
Amazon makes a "virtual assistant" called Alexa and [a bunch of hardware devices](https://www.amazon.com/Amazon-Echo-And-Alexa-Devices/b?node=9818047011). Customers can enable "skills" which are basically apps for Alexa. [Amazon lets anyone create a skill](https://developer.amazon.com/alexa). I've written a bunch, but a few of my most popular are below.

### Unofficial MLB Game Info - Python AWS Lambda Function
https://github.com/irlrobot/mlb_game_info || https://www.amazon.com/Rebuke-The-Net-Unofficial-Game/dp/B06XBYXKH9

This is my most popular skill during baseball season. I had to use "unofficial" in the name since I apparently don't represent Major League Baseball. It grabs the latest scores and next game for each team and puts that data into the format that Flash Briefing skills require. Customers enable the feed for each team they follow.

### Train My Brain - Python AWS Lambda Function
https://github.com/irlrobot/train_my_brain || https://www.amazon.com/Rebuke-The-Net-Train-Brain/dp/B073PRW6SB

A "brain training" game. It still helps pay for my AWS bill :) Just say "Alexa, play train my brain."

### Code Word - Python AWS Lambda Function
https://github.com/irlrobot/code_word || https://www.amazon.com/Rebuke-The-Net-Code-Word/dp/B077S3DCKN

A game similar to and inspired by the old gameshow ["Password"](https://en.wikipedia.org/wiki/Password_(game_show)). Jimmy Fallon has sorta revived it and [he plays it with guests occasionally](https://www.youtube.com/results?search_query=jimmy+fallon+password). Just say "Alexa, play Code Word."

# Blog Posts
I wrote a few blog posts for AWS when I worked for them between Oct 2015 and Nov 2018:
* [Terraform: Beyond the Basics with AWS](https://aws.amazon.com/blogs/apn/terraform-beyond-the-basics-with-aws/)
* [Automatically Delete Terminated Instances in Chef Server with AWS Lambda and CloudWatch Events](https://aws.amazon.com/blogs/apn/automatically-delete-terminated-instances-in-chef-server-with-aws-lambda-and-cloudwatch-events/)
* [AWS Sample Integrations for Atlassian Bitbucket Pipelines](https://aws.amazon.com/blogs/apn/aws-sample-integrations-for-atlassian-bitbucket-pipelines/)

# Speaking Events
I really don't like public speaking but I did it a few times for internal AWS events and [once publicly at ChefConf 2016](https://www.youtube.com/watch?v=NWhiWB87Wok&t=).


# Hobbies
My main hobby right now is flying drones. I primarily fly a [DJI Phantom 3 Pro](https://www.dji.com/phantom-3-pro) and I am currently studying to take the part 107 exam for my [Remote Pilot Certificate](https://www.faa.gov/uas/commercial_operators/become_a_drone_pilot/). I'm not into racing or showing off pictures/videos, I really just like to cruise around in first person view and see the world around me from another angle. I also play a lot of video games and watch TV with my wife when I'm not taking care of my daughter.
