Seq + nginx reverse proxy + lets encrypt
===============

Prerequisites:
--------------

* docker
* have a domain name that resolves
* replace <placeholders> in docker-compose.yml and nginx-conf/nginx.conf

To run:
-------

```
docker compose up -d
```

To renew certificats
--------------------

The letsencrypt certificates will expire after 90 days. Setup cron or similar to renew certificates using a process [like this one](https://www.digitalocean.com/community/tutorials/how-to-secure-a-containerized-node-js-application-with-nginx-let-s-encrypt-and-docker-compose#step-6-%E2%80%94-renewing-certificates).