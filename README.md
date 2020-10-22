## Dockerized Laravel Movie App

1. git clone la repo
2. in folderul src modificam .env.example in .env
3. tot in folderul src composer install --no-interaction --ignore-platform-reqs
4. rulam in terminal docker-compose up -d

Acum aplicatia ar trebui sa fie vizibila la 127.0.0.1:8033

## Ports

- **nginx** - `:8033`
- **mysql** - `:33051`
- **php** - `:4555`

