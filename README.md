# 66erCMS

This will be a new backend for the 66er

## Developer installation guide:

 - Follow https://docs.boltcms.io/5.0/installation/installation guide to install composer
 - Install MariaDB https://mariadb.com/
 - create a DB and a user
 - run `initialdb/dump.sql` on your newly created db
 - clone this repository, navigate into folder `sixtysix`
 - Copy `.env.template` and create a `.env` file.
 - Add your DB connection to to your `.env` file (MySQL/MariaDB section) and also alter `APP_SECRET`
 - run `bin/console bolt:add-user --admin` to add your admin user
 - Run `bin/console/ server:run` and go to http://localhost:8000/bolt
 - Done :-D