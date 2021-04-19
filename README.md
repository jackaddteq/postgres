# postgres

```
kubectl run postgresql-client --rm --tty -i --restart='Never' --namespace myspace --image docker.io/postgres:10 --env="PGPASSWORD=blahblah" --command -- psql --host dbhost -U dbuser -d dbname -p 5432

\l - list
\dt 

```
