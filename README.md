# Precompiled Binaries of MariaDB

## MariaDB v10.5.8

OSX was built locally on 2021-01-17 from: https://downloads.mariadb.com/MariaDB/mariadb-10.5.8/source/

All downloads sha256sums were verified to be consistent with those found on mariadb.com.

Building OSX required the following brew packages:
cmake jemalloc traildb/judy/judy openssl boost gnutls

mysql_secure_installation was modified to not provide a root user/pass if rootpass was not provided.
