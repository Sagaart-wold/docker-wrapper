# Docker-wrapper для интеграции фронтэнда и бекэнда Șagaart

## Запуск среды разработки

### 1. Клонировать docker_wrapper

```
git clone git@github.com:Sagaart-wold/docker-wrapper.git 
```
или
```
git clone https://github.com/Sagaart-wold/docker-wrapper.git
```


### 2. В папку 'docker_wrapper' склонировать backend

```
git clone git@github.com:Sagaart-wold/backend.git -b develop backend 
```
или
```
git clone https://github.com/Sagaart-wold/backend.git -b develop backend
```

### 3. В папку 'docker_wrapper' склонировать frontend

```
git clone git@github.com:Sagaart-wold/frontend.git -b develop frontend
```
или
```
git clone https://github.com/Sagaart-wold/frontend.git -b develop frontend 
```

### 4.  Скопируйте все из файла .env.example в файл .env и актуализируйте данные по необходимости

### 5. В папке 'docker_wrapper' запустить docker-compose.yml:

```
docker-compose up -d
```

### 6. Остановить:

```
docker-compose down
```

### 7. Пересобрать

```
docker-compose build --no-cache --pull
```
