Example

```laravel/install {projectName}```

Only if using sail
1) check mysql address by command
```docker inspect -f '{{range.NetworkSettings.Networks}}{{.IPAddress}}{{end}}' <MYSQL_CONTAINER_NAME>```
2) set address to DB_HOST= and FORWARD_DB_PORT=3306 