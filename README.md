#Flask on Docker 
A simple Python Flask application running in a Docker container.

### Run the Application

```sh
$ python app.py
```

The app can be reached in your browser at [http://localhost:8080/](http://localhost:8080/)


### Docker

```
docker build -t nexgtech/flask-demo-app:latest .
```

```
docker run -d -p 8080:8080 nexgtech/flask-demo-app:latest
```
