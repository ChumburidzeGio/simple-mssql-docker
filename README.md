# simple-mssql-docker

To run MSSQL with docker run `docker build -t mssql .` and then run with `docker run --name mssql -p 1433:1433 -d mssql`

You can also run container in detach mode, then check its name or id with `docker ps` and use `docker logs ContainerIdOrName -f`. We use _-f_ flag to _follow_ new logs.

To connect to the newly created database:

```
TYPE=mssql
HOST=46.101.209.153
PORT=1433
USERNAME=sa
PASSWORD=CorrectHorseBatteryStapleFor$
DATABASE=DemoData
```
