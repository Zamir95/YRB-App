# YRB-
SQL queries lab for IBM DB2 database

Script yrb_create.sql create YRB DB schema. Also populate tables with mock data. The script yrb_drop.sql is provided for convenience. It drops your copy of YRB DB from your DB2 schema space.

To create the YRB schema in your DB2 schema space: % db2 -tf yrb_create.sql

To drop the YRB tables in your DB2 schema space: % db2 -tf yrb_drop.sql
