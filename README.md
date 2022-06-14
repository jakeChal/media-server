To fire up the media containers:
`docker-compose --env-file path/to/.env up`

To check that container X has the IP from the VPN:
1. `docker-compose exec ContainerX sh`
2. `curl -4 ifconfig.io`
