# "json server" docker compose

## Purpose
Provides a docker compose to start "json server" as container.  
"json server" (https://github.com/typicode/json-server) is a server for mocking JSON apis by given _db.json_ data file.

## Configure

Fill the _db.json_ with the required objects. Multiple lists are possible.

## Execute

```bash
docker compose up
```
Server will be up at http://localhost:3000