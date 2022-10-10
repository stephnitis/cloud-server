# cloud-server

## [AWS Deployment](http://cloudserver-env.eba-b8rkdqta.us-west-2.elasticbeanstalk.com/)

## [Beanstalk Deployment](http://stephnitis-on-cloud-server-dev.us-west-2.elasticbeanstalk.com/)

### Process

- Created a new environment via AWS and Elastic Beanstalk using Node.js
- Configured terminal as a user for AWS account'
- Used IAM to manage access to AWS, created a user and group and set permissions
- Used access key to access through terminal
- `aws configure` in terminal with access key to set-up new environment
  - `eb init` to initialize directory with the EB CLI, creates the application
  - `eb create` creates a new environment
  - `eb deploy` deploys your source code to the environment
