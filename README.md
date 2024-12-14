# Spring To-do-list 🗓️

<br>

<p align="center">
  <a href="#-about-the-project">About the project</a> •
  <a href="#-technologies">Technologies</a> •  
<a href="#-license">License</a>

</p>

## 👩‍💻 About the project

This project is a REST API for task management, with authentication and authorization functionalities.

## 🚀 Technologies 

- [Java (17)](https://www.oracle.com/java/)  
- [Spring Boot](https://spring.io/projects/spring-boot)  
- [JPA / Hibernate](https://hibernate.org/)  
- [Maven](https://maven.apache.org/)  

## 📃 API documentation

#### Base URL

```https
  http://localhost:8080
```

#### Create a user

```https
  POST /users/
```

| Parameter   | Type       | Description                       |
| :---------- | :--------- | :---------------------------------- |
| `userModel` | `UserModel` | **Required**. Object with user data |

#### Create a task

```https
  POST /tasks/
```

| Parameter   | Type       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `taskModel` | `TaskModel` |  **Required**. Object with task-related data |

#### Get all tasks by user id

```https
  GET /tasks/
```

#### Updating a task by id

```https
  PUT /tasks/{id}
```
| Parameter   | Type       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `taskModel` | `TaskModel` |  **Required**. Object with task-related data |
 

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  Made with 💜&nbsp; by  Leandro Rodrigues
</p>
