# AWS Batch test run

The purpose of this project is to provision an AWS Batch compute environment, job definition and job queue using cloud formation template and execute a coouple of simple jobs using that infrastructure

## Project folder setup

```shell
.
├── aws-batch-test-run # --> Root folder
│   ├── build_and_push.sh # --> Script to build and push docker container image that will be used to execute the AWS Batch jobs
│   ├── buildspec.yml # --> Code build - buildspec/yml
│   ├── container # --> Batch job code
│   │   ├── code
│   │   │   ├── hello_mars.py
│   │   │   ├── hello_world.py
│   │   │   └── requirements.txt
│   │   └── Dockerfile # --> Docker container for the docker container image
│   └── template.yml # --> cfn template 
└── README.md
```
