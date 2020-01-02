# AWS CloudFormation WebApp Deployment Script

This is a project for [Cloud DevOps Engineer Nanodegree](https://www.udacity.com/course/cloud-dev-ops-nanodegree--nd9991).

### Description

Deploys a network and servers infrastructure to AWS account using CLI.

## Deployment instructions

There are two segments of code - one for networking and one for servers deployment. Each segment has its own `yml` file and `json` file with parameters.

sh scripts provided run create/update command with name of CloudFormation Stack Name specified as an argument. The name of stack is also should be used in yml and json files:

```
{stackname}
{stackname}.yml
{stackname}-parameters.json
```

Before running commands, fill the parameters files with proper values.

1. Run `sh create.sh udagram-network`
2. Run `sh create.sh udagram-servers`