### Following command creates htpasswd file using provided credentials

`docker run --rm --entrypoint htpasswd registry:2.7.0 -Bbn username pa$$w0rd | sudo tee -a /registry/auth/htpasswd`