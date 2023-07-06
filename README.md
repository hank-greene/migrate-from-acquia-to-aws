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
<img src="https://github.com/hank-greene/migrate-from-acquia-to-aws/blob/main/00-images/drupal-solar-architecture-01.png?raw=true" />


# install apache2 and drupal
* 06 install apache2, php, mariadb client, etc
* install drupal, configure to use 

# migrate drupal site code and data
* github code
* docroot

# deploy an EC2 instance for solr
* install solr
* create an index

# configure drupal for solr instance
