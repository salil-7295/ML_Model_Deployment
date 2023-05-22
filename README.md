# Deploy ML models with FastAPI, Docker, and Heroku

### Develop and save the model with this Colab

[Open Colab](https://colab.research.google.com/drive/1uaALcaatvxOu42IhQA4r0bahfdpw-Z7v?usp=sharing)

### Create Docker container

```bash
docker build -t app-name .

docker run -p 80:80 app-name
```

### Update the project to Github 

### Create Heroku project

```bash
heroku login
heroku create your-app-name
heroku git:remote your-app-name
heroku stack:set container
git push heroku main
```

[Referece](https://www.youtube.com/watch?v=h5wLuVDr0oc) :- AssembleyAI 
