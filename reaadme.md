java -jar target/demo1.jar



docker
plsql
microservices
kubernetes
ci/cd


git branch -m master main

 mvn spring-boot:run








your-full-stack-project/
│
├── backend/                   <-- Spring Boot Backend
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/
│   │   │   │       └── example/
│   │   │   │           └── demo/
│   │   │   │               ├── controller/
│   │   │   │               │   ├── TodoController.java
│   │   │   │               │   └── ...
│   │   │   │               ├── model/
│   │   │   │               │   ├── Todo.java
│   │   │   │               │   └── ...
│   │   │   │               ├── repository/
│   │   │   │               │   ├── TodoRepository.java
│   │   │   │               │   └── ...
│   │   │   │               ├── service/
│   │   │   │               │   ├── TodoService.java
│   │   │   │               │   └── ...
│   │   │   │               ├── DemoApplication.java
│   │   │   │               └── ...
│   │   │   └── resources/
│   │   │       ├── application.properties
│   │   │       ├── static/
│   │   │       └── templates/
│   │   └── test/
│   └── pom.xml
│
├── frontend/                  <-- React Frontend
│   ├── src/
│   │   ├── components/
│   │   │   ├── TodoList.js    <-- React components
│   │   │   └── ...
│   │   ├── App.js             <-- Main React app component
│   │   ├── index.js           <-- React app entry point
│   │   └── ...
│   ├── public/
│   │   ├── index.html         <-- HTML template
│   │   └── ...
│   ├── package.json           <-- Frontend dependencies and scripts
│   └── ...
│
├── Dockerfile                 <-- Docker configuration for backend
└── README.md


