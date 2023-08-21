# install solr
    1. copy solr to solr node
    2. aws -i ....pem solr-7.7.3-scr.tgz admin@54.85.178.218:/home/admin/

## install java
    1. java -version ( no response expected)
    2. sudo apt install open-jdk
    3. sudo apt update
    4. sudo apt install default-jre
    5. java -version ( expect runtime env build 11.0.18 ...)

## install solr
    1. sudo mv solr-7.7.3.tgz /opt/search
    2. cd /opt/search
    3. ls -l
    4. sudo tar xvf solar-7.7.3.tgz
    5. sudo ./solr start -force