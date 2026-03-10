# 🛒 Product REST API

A RESTful API built with Spring Boot and MySQL for managing products.

## 🛠️ Tech Stack
- Java 17
- Spring Boot 3.5.1
- Spring Data JPA
- MySQL
- Maven

## 🚀 How to Run

1. Clone the repository
   git clone https://github.com/vetri2601/product-api.git

2. Create MySQL database
   CREATE DATABASE productdb;

3. Update application.properties with your MySQL password

4. Run the application
   ./mvnw spring-boot:run

## 📌 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /products | Get all products |
| GET | /products/{id} | Get product by ID |
| POST | /products | Create new product |
| PUT | /products/{id} | Update product |
| DELETE | /products/{id} | Delete product |

## 📝 Sample Request

POST /products
{
"name": "iPhone",
"price": 999.0,
"category": "Electronics"
}
```

---

## Now push to GitHub

Go to cmd and run one by one:
```
git add README.md
```
```
git commit -m "Add README"
```
```
git push