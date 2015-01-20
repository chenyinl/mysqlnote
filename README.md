mysqlnote
=========
SELECT SHA1(UNHEX(SHA1("this_is_a_random_string")))

mysqld_safe --skip-grant-tables

output as CSV
mysql TABLENAME -u USERNAME -pPASSWORD -h IP < SQLFILE.sql | tr '\t' ','> OUTPUTFILENAME.csv
tr is used to translate characters

Dump without lock
--skip-add-locks
--lock-tables=false 
--single-transaction

Disc size
cat /etc/mysql/my.cnf

Find the parameter "datadir", which is /var/lib/mysql

Run a command to see the size of that directory

sudo du -h /var/lib/mysql
