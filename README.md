# Realm Object Server

Very basic Docker container for Realm Object Server

### Usage

```
docker run --name docker-realm -v <path_to_config_folder>:/etc/realm/ -p 9080:9080 -d stevenrudenko/realm-object-server
```
Example:
```
docker run --name docker-realm -v ~/docker-realm/configuration.yml:/etc/realm/configuration.yml -p 9080:9080 -d stevenrudenko/realm-object-server
```

Read configuration documentation on [Realm](https://realm.io/docs/realm-object-server/#setting-up-the-realm-dashboard)
