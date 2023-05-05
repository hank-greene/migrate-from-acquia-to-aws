# migrate-from-acquia-to-aws
Steps to migrate a Drupal CMS site from Acquia to AWS.  
Steps to instantiate a Solr EC2 instance and configure the Drupal site with search. 
# create the aws infrastructure
* 01 create vpc, network and debian instance
* 02 create an RDS(mysql) instance
* 03 create a EFS
* deploy a mount point
* mount the EFS in the debian instance
<img src="https://github.com/hank-greene/migrate-from-acquia-to-aws/blob/main/00-images/aws-achitecture.png?raw=true" />


# install apache2 and drupal
* install apache2
* install php
* install drupal, configure to use 

# migrate drupal site code and data
* github code
* docroot

# deploy an EC2 instance for solr
* install solr
* create an index

# configure drupal for solr instance
