```
docker compose up -d
```

```
docker exec php compose update
```

```
docker exec php php artisan key:generate
```

```
docker exec php chmod -R 777 storage
```

```
docker exec php php artisan migrate --seed
```

