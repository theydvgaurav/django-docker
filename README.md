
# Django Application Containerization

A django project which implements the Docker concept, and containerize a django application.


## Tech Stack

**Django, Docker**
## Run Locally

Clone the project

```bash
  git clone https://github.com/theydvgaurav/django-docker
```

Go to the project directory

```bash
  cd my-project
```

Build the docker image

```bash
  docker build . -t django-docker
```

Run the docker image

```bash
  docker run -p 8000:8000 --name django-docker  django-docker
```

