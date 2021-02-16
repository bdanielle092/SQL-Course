# Database Backup and Restore

This chapter will introduce you to the concept of how to make a backup of your database so that you can restore it back to a certain point in time.

At this point Carnival's database has been built and data has been imported. Now we must consider, should we make a backup of the database in case something were to go wrong with the data. We first ask ourselves a question...Is our database in a good place to back it up. If we know that everything has been imported smoothly then we can export the database dump file.

## Documentation and Videos to Watch Before Class

1. [pgAdmin Documentation Create Backup](https://www.pgadmin.org/docs/pgadmin4/4.30/backup_dialog.html)
1. [pgAdmin Documentation Restore Backup](https://www.pgadmin.org/docs/pgadmin4/4.30/restore_dialog.html)
1. [How to backup and restore postgreSQL database using pgAdmin 4](https://www.youtube.com/watch?v=GpZlVEONKpo)


## Practice: Create your backup file and restore you database

1. Use pgAdmin to create to create a SQL backup file. Then use this file to restore you database.

