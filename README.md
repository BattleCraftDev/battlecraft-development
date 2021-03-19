# Battlecraft development environment

## Instalation
```
$ git clone git@github.com:BattleCraftDev/battlecraft-development.git
$ git submodule init && git submodule update
$ git submodule foreach npm install
$ cp .env.example .env
```

Edit `.env` file before running `docker-compose`

## Usage
To start docker containers
```
$ docker-compose up -d
```

To stop docker containers
```
$ docker-compose down
```
