# IndyPool + IndyScan on localhost
Run:
```
docker-compose up
```

This will start up

- indyscan services (scanner, api, ui, elasticsearch)
- by default also kibana, you can opt-out by commenting it out in the `docker-compose.yml` file

You can now verify local connectivity by navigating to the following URLs: 

- main web GUI [http://localhost:3707/home/CANDY_DEV]
- Kibana elasticsearch [http://localhost:5601]
- Indyscan Daemon UI [http://localhost:3710]
