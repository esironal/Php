Php
===


This Repo contains php scripts to connect an android application with a remote Database

This is the connect code


<?php

define('DB_USER', "root");
define('DB_PASSWORD', "");
define('DB_DATABASE', "myDBname");
define('DB_SERVER', "localhost");

$con=mysql_connect(DB_SERVER,DB_USER,DB_PASSWORD);
mysql_select_db(DB_DATABASE,$con);
?>
