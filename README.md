# migrate from acquia to aws using aws cli 
Create the cloud infrastructure for the drupla site using aws cli.  
Migrate the Drupal CMS site from Acquia to AWS.  
Instantiate a Solr EC2 instance and configure the Drupal site with search.  
## TEMPARY aws architecture examples
https://awstut.com/en/2023/02/18/3-ways-to-access-s3-from-private-subnet-en/


# create the aws infrastructure
* 01 create vpc, network and debian instance
* 02 create an RDS(mysql) instance
* 03 create a EFS
* 04 create mount point
* 05 mount the EFS in the debian instance
<img src="https://github.com/hank-greene/migrate-from-acquia-to-aws/blob/main/00-images/Drupal-AWS-VPC.png?raw=true" />


# install apache2 and drupal
* 06 install apache2, php, mariadb client, etc
* 07 install drupal and configure for drupal site

# migrate drupal site code and data
* 08 migrate the aquia site
* github code
* docroot

# deploy an EC2 instance for solr
* 09 install solr
* create an index

# configure drupal for solr instance
