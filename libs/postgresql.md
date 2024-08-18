## postgres notes

```bash
This formula has created a default database cluster with:
initdb --locale=C -E UTF-8 /usr/local/var/postgresql@14
For more details, read:
https://www.postgresql.org/docs/14/app-initdb.html

To start postgresql@14 now and restart at login:
brew services start postgresql@14
Or, if you don't want/need a background service you can just run:
/usr/local/opt/postgresql@14/bin/postgres -D /usr/local/var/postgresql@14
```