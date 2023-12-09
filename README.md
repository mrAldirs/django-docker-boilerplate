<div align="center">
  <img width="30%" src="https://bunnyacademy.b-cdn.net/what-is-docker.png">
</div>

# Boilerplate Django With Docker

### Cloning the repository

--> Clone the repository using the command below :
```bash
git clone https://github.com/mrAldirs/django-docker-boilerplate.git

```

##

### Run Docker Compose

--> Run docker-comose.yml using the command below :
```bash
docker-compose up -d

```

##

### Create App and Migrate

--> Create new app using the command below :
```bash
docker-compose run web startapp nameapp

```

--> Make migrations using the command below :
```bash
docker-compose run web makemigrations

```

--> Migrate using the command below :
```bash
docker-compose run web migrate

```

#
