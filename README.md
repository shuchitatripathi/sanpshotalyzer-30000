# sanpshotalyzer-30000
demo project to manage AWS EC2 instances snapshots

##About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

##Configuration

shotty uses the Configuration file created by aws cli e.g.
'aws configure --profile shotty'

##Running

'pipenv run python shotty/shotty.py <command> <--project=Project>'

*command* is list, start or stop
*project* is optional
