# Configure DB Access

## set MYSQL_HOST in the env
```
> sudo touch /etc/profile.d/mysql_set_env.sh  
> sudo vi /etc/profile.d/mysql_set_env.sh  
 export MYSQL_HOST= [ database name ] . [whatever ] . us-east-1.rds.amazonaws.com  
  

> sudo reboot```

