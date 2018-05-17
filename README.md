# Elastic-Beanstalk

Guardar BD en instancia:

mysqldump -u root -p --opt gfsguate_sys > gfsguate_sys.sql

Subir al RDS:

mysql -h aa1lva7losjexya.cddrx6jm0v02.us-west-2.rds.amazonaws.com -u root -p gfsguate_sys < gfsguate_sys.sql
 
