# Configuration Items

1. database connect and credential info
2. EFS IP Address found from terraform show, aws_efs_mount_target


# Reference data, raw data

1: database connect credentials, etc ... .
2: export the database mysql ...
3: tar up the site ... 


Collect the database configuration (databasename, username, password, host ip) from the existing site.
Find it in file /sites/default/settings.php.
Look for the following entry.

$database = array (
  'default' =>
  array (
    'default' =>
    array (
      'database' => 'site_to_be_migrated_db_name',
      'username' => 'site-to-be_migrated_user_name',
      'password' => 'site-to-be-migrated-password',
      'host' => 'therdsinstance.abcdefb.us-east-1.rds.amazonaws.com',
      'post' => '3306',     /* or whatever it is */
      'driver' => 'mysql',  /* this site uses mysql */
      'prefix' => '',
    ),
  ),
);
 
    

 
