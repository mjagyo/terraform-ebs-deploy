# DevOps Engineer - Technical Test

## Testing goals
  * With this test, we want to see your ability to create an entire infrastructure from scratch as well as your skills as a system administrator.

## The task
  * Your task is to provision an AWS Elastic Beanstalk environment via their API, with a deployment script using GitHub Actions upon merge into the prod branch.

## The solution
  * In your solution please focus on readability, maintainability, and strong DevOps methodologies. We expect a clear way to recreate your setup.

  * Step 1: Create an AWS Elastic Beanstalk environment with an API call. This should include a load balancer, elastic scalability based on CPU usage limits, access via port 80, and a PostgreSQL database with Multi AZ.

  * Step 2: Create a workflow file for GitHub Actions to deploy a standard Node JS back end (built using yarn package manager) to Elastic Beanstalk. The back end should also automatically execute database migrations using Sequelize, a Node JS package.

  * Make sure to include a requirements.txt so that all roles can be installed when ran.
  * A clean bare minimum working infrastructure is preferred. Do not skip security considerations.

## When you are finished
  * Submit your solution to info@stationfive.com for review with subject line "DevOps Engineer - Technical Test Submission"
  * Make sure your README tells us how to run it.

## Bonus Points
  * If you can document all aspects of your code in the README and within the code itself.
