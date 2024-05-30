# Run tests in CI/CD with GitHub Actions and Docker

Steps to run tests:
1. Get a mongo image: `docker pull mongo`
2. Start database: `docker container run --name mydatabase --publish 27017:27017 -d mongo`
3. View containers: `docker ps`
4. Run tests: `npm test`