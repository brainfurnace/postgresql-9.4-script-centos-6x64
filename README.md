# postgresql 9.4 script for centos 6.x64

For use on a clean CentOS box only.

This script installs PostgreSQL 9.4 along with Webmin.

It also creates a minimally privilaged user (pgadmin), disables root log in, sets IP tables and configures Webmin for managing PostgreSQL.

A self-signed SSL is also created and pga_hba.conf is set to MD5 and postgresql.conf is updated for SSL.

You can change the SSH port as well as the user name to whatever you like.
