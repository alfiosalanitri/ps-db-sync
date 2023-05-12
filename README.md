# ps-db-sync
A simple bash script to import/export a prestashop database to/from prestashop root directory.

## Installation
- `sudo chmod +x /path/to/ps-db-sync`
- `sudo ln -s /path/to/ps-db-sync /usr/local/bin/ps-db-sync`

## Usage
- `cd /to/prestashop/website/directory/`
- `ps-db-sync -e` to export the database to /prestashop/website/directory/dump.sql
- `ps-db-sync -i` to import the database from /prestashop/website/directory/dump.sql (note: the script will export a dump.sql.bkp before importing the database)

# Author:
ps-db-sync is written by Alfio Salanitri www.alfiosalanitri.it and are licensed under the terms of the GNU General Public License, version 2 or higher.
