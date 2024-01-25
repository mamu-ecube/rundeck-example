# Rundeck Demo

1. `docker compose up`
2. http://localhost:4440 öffnen
3. User `admin`, password `admin` verwenden.
4. `nodes.yml` nach `/var/lib/docker/volumes/rundeck_data/_data/test` kopieren.
5. Settings > Edit Nodes > Sources > Add a new Node Source > File Source auf `/home/rundeck/server/data/test/nodes.yaml`
6. Settings > Key Storage > Add or Upload a Key > Password

