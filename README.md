# Deploy-containerized-applications-to-the-EC2-instance-with-only-one-command.

You have a SpringBoot application with a REST API. This API fetches info about customers from a MySql database and returns it.

It is worth mentioning that this tutorial works for an application written in any programming language as long as it runs on a Docker container.

When I test it locally on my PC first I build a docker image for my application and then I use docker-compose to spin up containers one for the MySql database and another for the SpringBoot app.
