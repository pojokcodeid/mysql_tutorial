- buat folder data dalam root directory
- Perintah menjalankan

```
docker-compose up
docker-compose up -d
```

- Perintah Down

```
docker-compose down
```

- down dan hapus

```
docker-compose down --volumes --rmi all
```

# Panduan Remote Container

- list container

```
docker ps -a
```

- remote container

```
docker exec -it <nama_container_mysql> bash
```

- login mysql

```
mysql -u root -p
```
