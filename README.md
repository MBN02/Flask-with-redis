# Flask-with-redis
Build a python web app using flask and redis.

1. docker build -t app-name Dockerfile location
  * example : docker build -t myapp .
  
2. Run the redis database before running the myapp 
  * docker run --name redis -d redis 
  
3. Link your myapp with redis database 
  * docker run --link redis -p 5000:5000 -d myapp
  
# Access myapp using localhost:5000
