# Smart Notes 
A Django web app built using Docker and Docker Compose. 

### Running Locally

1. Ensure Docker and Docker Compose are installed.
2. Build and run containers: 
```shell 
docker compose up -d --build
```

3. Run migrations:
```shell
docker compose run web python manage.py migrate
```

4. Access the app via [http://localhost:8000](http://localhost:8000)


### Additional Info
This project is based on the course "Django Essential Training", located [here](https://www.linkedin.com/learning-login/share?account=73722380&forceAccount=false&redirect=https%3A%2F%2Fwww.linkedin.com%2Flearning%2Fdjango-essential-training%3Ftrk%3Dshare_ent_url%26shareId%3D0VeWWa0gTUKW8HJ3%252BKDpaQ%253D%253D).