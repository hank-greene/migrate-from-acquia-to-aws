# mount efs
## from the drupal instance

ssh into the drupal instance
sudo su -
mkdir /var/www
mkdir /var/www/html
exit

sudo mount -t nfs -o nfsvers=4.1,rsize=1048576,hard,timeo=600,retrans=2,noresvport <efs mount point ip>:/ /var/www/html


## from the solr instance

ssh into the solr instance
sudo su -
mkdir /opt/search
exit

sudo mount -t nfs -o nfsvers=4.1,rsize=1048576,hard,timeo=600,retrans=2,noresvport <efs mount point ip>:/ /opt/search

