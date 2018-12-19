# Dev Guide
Guide and useful resources 


## MySQL Guides


* [Using dbsake to recover table structure from .frm](https://www.percona.com/blog/2015/12/16/recovering-table-structure-from-frm-files-using-dbsake/) -  collection of command-line tools that perform various DBA related tasks for MySQL. Use this helper command to ease the process ``for tbl in `ls -l /var/lib/mysql/_data/db/*.frm`; do ./dbsake frmdump $tbl >> import.sql; done``
* [Restore MySQL InnoDB from .ibd files](https://www.voxteneo.com/restoring-tables-mysql-database-frm-ibd-files-available/) - Your server crashed and you recover only the frm and idb files. If you have only the idb files, it works also but you need the SQL scripts with the DB structure


## Contributing

Please read 
