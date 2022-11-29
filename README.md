# Тестовое задание

### Для проверки тестового задания на рабочей машине необходимо:

- установит Docker (+docker-compose)
- создать директорию для запуска сервера:
```
mkdir testwork
cd testwork
```
- скопировать в данную директорию файлы docker-compose.yaml и .env
- запустить сервер:
```
docker-compose pull
docker-compose up -d
```

### В базе данных уже имеется три позиции. Т.е. доступны следующие URL:
```
localhost/item/1/
localhost/item/2/
localhost/item/3/
```
