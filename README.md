## URL: https://poisonsvb.com

---

### 서버 시작하기

Backend .env file

- config/.env

```
DJANGO_SECRET_KEY=
DJANGO_PASSWORD=
```

```shell
$ git clone https://github.com/SV-Team-B/docker.git
$ git submodule update --recursive --remote --init
$ cd frontend
$ yarn
$ yarn build
$ cd ..
$ docker-compose up --build -d
```

### 개발 서버 시작하기

```shell
$ git clone https://github.com/SV-Team-B/docker.git
$ git submodule update --recursive --remote --init
$ docker-compose -f docker-compose-dev.yml up -d
```
