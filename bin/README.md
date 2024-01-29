# Hospital Appointment System Accenture

Recently, several hospitals in the area have received a series of computer attacks and it has been proposed to renew the appointment control system at the AccWe hospital, since it is what has not been updated for the longest time. The developers have saved part of the previous project and cleaned it to avoid possible errors, especially updating libraries. Your task will be to implement, arrange and develop the different needs of the hospital regarding appointment management.

🎯 Objectives:
The main objective is to finish implementing and developing the appointment management of the Backend project. This project uses old versions of JAVA, specifically JAVA 8. Therefore, it is requested to develop the following tasks:

Your first task will be to create appointments using the API. You should keep in mind the limitations when it comes to creating appointments. Make sure you adhere to the specifications made in JUnit, as they are an essential aid for code development. You only need to modify the AppointmentController.java file.

The second task is related to the fact that the created entities are not being "tested", and therefore, possible errors may arise due to poor implementation. To solve this, different "JUnit" tests must be created for each of the entities in the EntityUnitTest.java file, as well as each of the controllers for these entities in the EntityControllerUnitTest.java file, which is located in the tests directory .

Make sure you make clean code. Since you are working in a hospital, you will be expected to follow strict measures to ensure the code is acceptable. Therefore, you must write code that is free of bugs and vulnerabilities, especially exploits.

We want to make a scalable deployment of the API, for this we consider using Kubernetes. Create a Dockerfile to run a MySQL database and the microservice. For this last requirement, a Multistage Dockerfile is requested where the tests are executed first, and if they all pass, the microservice is compiled and executed. The names of the Dockerfiles will be Dockerfile.mysql and Dockerfile.maven, respectively.

*Extra OPTIONAL: Develop a UML diagram with all the relationships between classes. Documentation within the repository will be positively valued.

*IMPORTANT: AppointmentController.java', 'EntityUnitTest.java' and 'EntityControllerUnitTest.java' are the only modifiable files. The rest of the files are NOT and are protected.