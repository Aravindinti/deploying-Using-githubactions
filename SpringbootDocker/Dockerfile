FROM openjdk:17

COPY ./target/Demo.jar demo.jar

WORKDIR .

#When wee run this appliation it runs within the container on its port 8080
#any port with in the conatiner is not accessible to outside world unless publshed explicitly
#in other works we have to bind host machine port with the container port
EXPOSE 8080
CMD ["java","-jar","demo.jar"]
