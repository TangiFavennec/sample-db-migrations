# sample-db-migrations
Database migration for some other repositories projects

## Initial setup

Make sure you have flyway installed.
if not, run ```brew install flyway``` (in case you do not have it, intall brew https://brew.sh/).

## Migrate

run ```flyway -configFiles=./conf/flyway.conf -X migrate```
