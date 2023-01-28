# docker-gs-ping-roach
 
A slightly more advanced Go server/microservice example for [Docker's Go Language Guide](https://docs.docker.com/language/golang/). 

Notable features:

* Extends the basic example introduced in [olliefr/docker-gs-ping](https://github.com/olliefr/docker-gs-ping).
* Uses [CockroachDB](https://github.com/cockroachdb/cockroach) database engine.
* Introduces [Docker Compose](https://docs.docker.com/compose/).

* add .env file for rest-server container to export environment variable for database 

* run docker compose configure for syntax error before build

# Keypoints

* docker run -d -p 8080:8080 docker-gs-ping
*  When you run this command, you’ll notice that you were not returned to the command prompt. This is because our application is a REST server and will run in a loop waiting for incoming requests without returning control back to the OS until we stop the container.

## Contributing

This was written for an _introduction_ section of the Docker tutorial and as such it favours brevity and pedagogical clarity over robustness. 

Thus, feedback is welcome, but please no nits or pedantry. Ain't nobody got time for that 🙃

## License

[Apache-2.0 License](LICENSE)
