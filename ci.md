Git, Docker, Automated Testing and Continuous Integration

Purpose: Automated provisioning of environments/infrastructure with self-serviced automated tools depending on the development/IT needs.

* Challenges faced by organizations:

* Unavailability of environments
* Lack of environment configuration skill sets
* High lead time in environments provisioning

* What is Continuous Integration?

It is a development practice where developers integrate code into a shared repository several times a day which supports integrating new functionality with the existing code. This integrated code also ensures that there are no errors in the runtime environment, allowing us to check how it reacts with other changes.

The most popular tool used for continuous integration is “Jenkins” while GIT is used for Source Control Repository. Jenkins can pull the latest code revision from GIT repository and produce a build which can be deployed to a server.

* What is Continuous Delivery?

Continuous Delivery is the capability to deploy the software to any environment at any given time including binaries, configuration, and environment changes, if any.

* What is Continuous Deployment?

Continuous Deployment is an approach where the development teams release software in short cycles. Any change a developer makes gets deployed all the way to production.

* What is Docker?

Docker is a Containerization platform which packages the application and all its dependencies together in the form of Container to ensure that the application works seamlessly in any environment.

* How does a Docker help in CI/CD?

Dockers help developers to build their code and test their code in any environment to catch bugs early in the application development life cycle. Dockers help streamline the process, save time on builds, and allows developers to run tests in parallel.

Dockers can integrate with source control management tools like GitHub and Integration tools like Jenkins. Developers submit the code into GitHub, test the code that automatically triggers a build using Jenkins creating an image. This image can be added to Docker registry to deal with inconsistencies between different environment types.

* Technical Solution

Developers commit the code to their repository that usually triggers a build on a Continuous Integration Server. The build process might differ depending on the application you are building but normally you do things like Compile, run Test Cases, Build the application, and then Deploy the app into an Application Server.

* Continuous Integration with Docker

One method to fit the Docker in the CI process is to have the CI server build the Docker Image after it has built the application. The application goes inside the image, and the image is then pushed to Docker hub. On another host, either QA/Dev/Production environment, pull the nearly completed build from the Docker Hub and run the Container which will run your application. In the CI server, you could even have your Compile and Testing done as part of the Image build.

Benefits
* Nullify the issue of inconsistent environment setups
* Any machine that is running a Docker can use a Docker Image
* Save time on build and set up processes
* Allow developers to run tests in parallel
* Separation of concerns in DevOps: developers can focus on developing apps and system administrator
* can focus on deployment

Improved Version Control by committing changes to your Docker images for standardizing environment
