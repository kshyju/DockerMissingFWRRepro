#### Sample dotnet isolated app with docker-compose.

##### To run locally.
1. Clone the repo.
2. Open a terminal in the root of the repo (where `docker-compose.yml` file is present).
3. Run `docker-compose build`. Wait for it to complete.
4. Run `docker-compose up`. This will start the azure function app.
5. Open a browser and navigate to `http://localhost:8080/api/Function1`

