Objective: Use CM tools such as Puppet, Ansible, or Chef to automate the installation of basic Drupal or WordPress. Setup a sample site. Automate the solution using Cloudformation template.

Deliverable: A cloudformation template that accepts user inputs as parameters where applicable ( for example, Admin password). This template should setup VPC, create subnets, launch a CM instance, pull the necessary code (modules, classes, recipes etc) from a GIT repo (or S3), and configure the web instance for basic Drupal or Wordpress setup.

================================================================================
Approach: Created Ec2 Instance and new VPC and created the chef-cookbooks in local PC and pushed to GitHub


Step-1: Use the CloudFormationWP.JSON to create the stack in EC2.

Step-2: Enter Stack Name

Step-3: Enter DBPassword, DBUser

Step-4: Select the KeyName existing

References:http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/cfn-sample-templates.html
           http://github.com/opscode/chef-repo/tarball/master
