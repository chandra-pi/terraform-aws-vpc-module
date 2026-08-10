# VPC Module
* This module is developed for joindevops company. Projects inside the joindevops use this module create thier vpc

## Inputs
* project (required) - users should specify their project name
* environment (required) - users should specify their environment name
* cidr_block (optional) - users should provide their cidr_block, default is 10.0.0.0/16

## Outputs
* vpc_id - Exports VPC ID created