laatste update: 
Status: FAALT - fout - 
<br />
<b>Warning</b>:  mysqli::__construct(): php_network_getaddresses: getaddrinfo for mariadb failed: Temporary failure in name resolution in <b>/var/www/html/intranet/sein514/sein514/inc/db.php</b> on line <b>9</b><br />
<br />
<b>Fatal error</b>:  Uncaught mysqli_sql_exception: php_network_getaddresses: getaddrinfo for mariadb failed: Temporary failure in name resolution in /var/www/html/intranet/sein514/sein514/inc/db.php:9
Stack trace:
#0 /var/www/html/intranet/sein514/sein514/inc/db.php(9): mysqli-&gt;__construct('mariadb:3306', 'sein514', Object(SensitiveParameterValue), 'sein514')
#1 /var/www/html/intranet/sein514/sein514/inc/sein514.php(3): include_once('/var/www/html/i...')
#2 /var/www/html/intranet/sein514/sein514/status.php(3): include_once('/var/www/html/i...')
#3 {main}
  thrown in <b>/var/www/html/intranet/sein514/sein514/inc/db.php</b> on line <b>9</b><br />
