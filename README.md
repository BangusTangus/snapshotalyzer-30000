# snapshotanalyzer-30000

Demo project to manage instance snapshots

## About

This project is a demo, and uses boto3 to manage
instance snapshots

## Configuring

shotty uses the configuration file created by the AWS CLI e.g.

`aws configure --profile shotty`

## Running

`pipenv run Python3 "shotty/shotty.py <command> <subcommand>
 <--project=PROJECT>"'

*command* is instances, volumes, or snapshots
*subcommand* - depends on command
*project* is optional
