In this example I first configure a Flow with 2 Steps in FlowConfiguration.java and then run:

1) Flow first and another Step after - FlowFirstConfiguration.java
2) Another step and then the Flow - FlowLastConfiguration.java

---

####To run:
- First create and run database:
`
docker build -t mysqldb . && docker run -d -p 3306:3306 mysqldb
`

- Then run the app with `mvn spring-boot:run`