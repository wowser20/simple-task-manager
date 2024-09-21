# Simple Task Manager

Starting simple task manager built with Go and PostgreSQL database. 


To start the local docker postgres container, run:
```bash
$ make postgres-container
```

To create the schema, run:
```bash
$ make schema
```

To migrate the schema up files to database, run:
```bash
$ make migrate-up
```

To migrate the schema down files to database, run:
```bash
$ make migrate-down
```



