# README


1. docker pull postgres
2. docker run -d --name RailsExercisesDB -p 5432:5432 -e POSTGRES_PASSWORD=pass123 postgres
3. docker exec -it RailsExercisesDB bash
4. psql -h localhost -U postgres