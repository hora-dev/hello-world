
Classic **Hello World!** app built with Java 21

Running the example,

1. Ensure you're running Java 21 on your machine and java Maven installed on your machine.
2. Run:
   `mvn clean package && docker-compose up && docker-compose down`
3. You should see something like:

`Creating network "hello-world_default" with the default driver`

`Creating hello-world-app ... done`

`Attaching to hello-world-app`

`hello-world-app | Hello, World!`

`hello-world-app exited with code 0`

