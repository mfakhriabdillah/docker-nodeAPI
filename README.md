
# Dockerized Node API

This repository contains simple REST API (built with Node JS), and i containerize this API using Docker.


## Requirements

- NodeJS
- npm
- mongoDB



## Deployment

To execute this project run

```bash
  npm run dev
```
To deploy this project using Docker run

```bash
docker compose up -d 
```

## Running Tests

To run tests, run the following command

```bash
  npm run test
```


## API Reference

#### Register new user

```http
  POST /api/auth/register
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `name` | `string` | **Required**. Your user name |
| `email` | `string` | **Required**. Your email address |
| `password` | `string` | **Required**. Your custom password |


