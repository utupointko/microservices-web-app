# microservices-web-app

## Python Microservices Web App

### About The Project

Contains:

- Operations with products
  - Creation, Reading, Editing, Deleting (REST API)
  - Likes
- Message queue (cloud monitoring and analysis)

TODO:

- User authorization/authentification with e-mail verification
- Form validation
- Pagination
- Operations with products
  - Search
  - Comments

Developed for purpose of learning the microservices architecturre.

Why microservices? Using Python microservices allows you to break up your apps into smaller parts that communicate with each other. This can make it simpler to scale the application based on the traffic. Also, the separation of concerns makes it easier to work on just one part of the app at a time.

### Built With

- React
- Django
- Flask

### Getting Started

### Prerequisites

- docker, docker-compose
- npm

#### Installation

1. Clone the repository

    ```shell
    git clone https://github.com/utupointko/microservices-web-app`
    ```

2. Get a free API Key at <https://www.cloudamqp.com/>

3. Enter your API Key in each `producer.py` and `consumer.py` of admin and main applications

4. Run admin application ([instruction](https://github.com/utupointko/admin-django/blob/df600d7e7fda58067d58561ecc0aa8cf6b93ce20/README.md))

5. Run main application ([instruction](https://github.com/utupointko/main-flask/blob/b3f9f3ba119ccc1dee1693d187048696836bfd44/README.md))

6. Install NPM packages and run react application

    ```shell
    npm install
    npm run
    ```

### Languages, Databases, Middlewares and others

- Python, Typescript
- MySQL
- Bootstrap
- CloudAMQP (RabbitMQ)
