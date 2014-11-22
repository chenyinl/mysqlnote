mysqlnote
=========
SELECT SHA1(UNHEX(SHA1("this_is_a_random_string")))

mysqld_safe --skip-grant-tables

output as CSV
mysql TABLENAME -u USERNAME -pPASSWORD -h IP < SQLFILE.sql | tr '\t' ','> OUTPUTFILENAME.csv
