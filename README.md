### Use

To start the XPS DCC web application, type the following on the command line

links --config=config.0.9.8 src/startXPS.links

This assumes that appropriate databases are available and a running PostgreSQL server. More information about this will be provided in INSTALL.md

### Docker

A demo image is available at https://hub.docker.com/repository/docker/vcgalpin/xps_dcc_app/

To run this image, use
```
docker run -d \
  --name tempdb_simple_web \
  -p 8080:8080 \
  -v tempdb_simple_web_pgdata:/opt/postgres-data \
  vcgalpin/xps_dcc_app:tempdb_simple_web_test
```



