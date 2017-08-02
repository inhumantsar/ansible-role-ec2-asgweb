# ec2-asgweb

## What?

Creates an autoscaling group of web servers operating on 80, 443, and 22.

## Why?

... short paragraph describing why this role does what it does ...

## How?

todotodotodo

The scheduled actions code *should* be rendered obsolete in Ansible 2.4, due for release Q3/Q4 2017. 

### Requirements
* boto3 (pypi)
* jdauphant.ssl-certs (ansible-galaxy)
* [q](https://github.com/zestyping/q) (pypi - for debugging ec2_asg_scheduled_actions)
