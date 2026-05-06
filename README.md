# Student Management Application

## 📌 Description
Application web CRUD pour la gestion d'étudiants, développée dans le cadre d'un apprentissage personnel de **Spring Boot**.  
Elle permet d'ajouter, modifier, supprimer et afficher la liste des étudiants.

## 🛠️ Technologies utilisées
| Technologie | Version |
|-------------|---------|
| Java | 21 |
| Spring Boot | 3.4.2 |
| Spring Data JPA | - |
| Thymeleaf | - |
| MySQL | 8.x |
| Maven | - |
| Bootstrap | 4.3.1 |

## ✨ Fonctionnalités
- ✅ Afficher la liste des étudiants
- ✅ Ajouter un nouvel étudiant
- ✅ Modifier les informations d'un étudiant
- ✅ Supprimer un étudiant
- ✅ Interface responsive avec Bootstrap

## 🚀 Installation et exécution

### Prérequis
- Java 21
- MySQL 8.x (XAMPP ou installation standalone)
- Maven (ou utilisez le wrapper `mvnw` inclus)

### Étapes

1. **Cloner le projet**
```bash
git clone https://github.com/NOuhmou/student-management-app.git
cd student-management-app
````
2. **Créer la base de données MySQL**
```bash
CREATE DATABASE db_crud;
````

3. **Configurer l'accès MySQL **
```bash
spring.datasource.url=jdbc:mysql://localhost:3306/db_crud
spring.datasource.username=root
spring.datasource.password=
````
4. **Lancer l'application**
```bash
./mvnw spring-boot:run
````
5. **Accéder à l'application**
```bash
Ouvrez votre navigateur à l'adresse : http://localhost:8080/students
````
6. ** Structure du projet**
student-management-app/
├── src/main/java/com/app/web/
│   ├── controller/      # Contrôleurs Spring MVC
│   ├── entity/          # Entité JPA
│   ├── repository/      # Accès aux données (JpaRepository)
│   └── service/         # Logique métier
├── src/main/resources/
│   ├── templates/       # Vues HTML (Thymeleaf)
│   └── application.properties
└── pom.xml
7. ** Aperçu**

