# Instructions
J.C. Sciaccotta 1983083

**TODO:** Add your screen captures to a new directory called [images](images).

**HINT:** Embed your screen captures as requested in the sections below. You can embed the image using the following syntax:

```
![Screen Capture #1](images/my-screen-capture.jpg)
```

The first argument is the Alt-text for the image. The second argument is the path to the image. Make sure your images are readable and that you save them in a JPG or PNG format.

HW5

Your GitHub account showing that is has been forked from the depaulcdm/spring- petclinic repository. This doesn’t actually need an image – I can see it from your repository.

Your GitHub Actions dashboard showing a successful first build.
![Successful First Build](images/create_maven_workflow.png)

Your GitHub repository with the readme.md file selected showing the code that you changed to update the badge.
![Updated Badge](images/update_badge.png)

Your GitHub repository with the readme.md file selected showing the build success status after you’ve updated the badge markdown.
![update readme workflow](images/update_read_me_workflow.png)
![readme Successful Build 1](images/read_me_initial_build_succeed_1.png)
![readme Successful Build 2](images/read_me_initial_build_succeed_2.png)

The section of the POM file showing the coordinates after you’ve commented them out.
![Commented Out Coordinates](images/commented_out_maven.png)

Your GitHub Actions dashboard showing the unsuccessful build after the breaking change.
![Pom Fail Workflow](images/pom_fail_workflow.png)

Your GitHub repository with the readme.md file selected showing the build failed status after the GitHub workflow fails.
![readme Status Fail](images/pom_change_build_fail.png)

The section of the POM file showing the coordinates after you’ve fixed them.
![Fixed Coordinates](images/pom_fixed_coordinates.png)

Your GitHub Actions dashboard showing the successful build after the breaking change has been fixed.
![Pom Fix Workflow](images/pom_fix_workflow.png)

Your GitHub repository with the readme.md file selected showing the build success status after the GitHub workflow has recovered.
![readme Pom Fix Status Pass](images/read_me_pom_fix_pass.png)

DOCKER

Your dockerfile. Please provide a link to this file rather than a screen capture.

https://github.com/jsciacco/spring-petclinic/blob/master/dockerfile 

Your running docker instance as shown by a ps command.
![Docker run](images/docker_run.png)

Your browser accessing the main page of the website from your local container.
![Docker browser command](images/browser_local_command.png)
![Docker browser main page](images/browser_local_container.png)

DOCKER COMPOSE - MYSQL ONLY

The output from the docker-compose up command.
![Docker compose up command](images/compose_up_my_sql_only.png)

Your browser accessing the “Veterinarians” page of the website from your local container when you run the application from the host system.
![Docker access vet]

A section of the stack trace generated when you attempt to run the application container that has been updated to use MySQL.
![Docker section stack](images/mysql_fail.png)

DOCKER COMPOSE - APP SERVER AND MYSQL

Your updated docker-compose.yml file containing the application server, built from your local Dockerfile, and the existing MySQL configuration.
Please provide a link to this file rather than a screen capture.

https://github.com/jsciacco/spring-petclinic/blob/master/docker-compose.yml

Your updated application-mysql.properties file containing the URL change for the database server. Please provide a link to this file rather than a screen capture.

https://github.com/jsciacco/spring-petclinic/blob/master/src/main/resources/application-mysql.properties

The output from the docker-compose up command.
![Docker compose up App Server 1](images/compose_up_app_mysql_part1)
![Docker compose up App Server 2](images/compose_up_app_mysql_part2)

Your browser accessing the “Veterinarians” page of the website from your local container.
![Docker access vet App](vet_mysql_app)
