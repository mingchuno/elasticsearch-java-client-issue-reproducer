# README

```bash
docer compose up -d
./gradlew run
```

```
Exception in thread "main" co.elastic.clients.json.JsonpMappingException: Error deserializing co.elastic.clients.elasticsearch.security.IndicesPrivileges: Invalid enum 'indices:admin/aliases' (JSON path: remote_monitoring_agent.indices[1].privileges[3]) (line no=1, column no=3260, offset=-1)
```

Issue: https://github.com/elastic/elasticsearch-java/issues/317