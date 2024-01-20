# Site em django

## Comandos via diretório principal

docker build -t site-em-django .

docker run -db 8000:8000 site-em-django

## Comandos via diretório principal(compose)

docker compose up -d

## Comando via Docker Hub

docker run -dp 8000:8000 gdantass/site-em-django