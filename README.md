# MariaDB

Configure mariadb without HA. See `mariadb-ha` role for Galera cluster configuration.


## Configuration
|Var|Default value|Description|
|---|-------------|-----------|
|mariadb_local_only|`True`|Don't accept remote connections when set to `True`.|
|mariadb_root_password| |The password to set for root.|
|mariadb__databases|`[]`| List of dicts of databases/users to create. Each entry has a name, user and passwort attribute, specifying a database and a user to access this database. The user will be granted all privileges on the database. |
