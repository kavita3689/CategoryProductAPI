# Category-Product-API-Spring-Boot
Category &amp; Product Management API using Spring Boot A RESTful API for managing categories and products with CRUD operations, pagination, and one-to-many relationships using Spring Boot, JPA, Hibernate, and MySQL.


# 🛍️ Category & Product Management API

A **Spring Boot** REST API that allows users to manage **categories** and **products** with full **CRUD operations, pagination, and one-to-many relationships**. Built using **Spring Boot, JPA, Hibernate, and MySQL**.

## 🚀 Features
✅ **Category Management** (Create, Read, Update, Delete)  
✅ **Product Management** (Create, Read, Update, Delete)  
✅ **One-to-Many Relationship** (One Category → Multiple Products)  
✅ **Server-Side Pagination** for efficient data handling  
✅ **RESTful APIs** following best practices  
✅ **Annotation-based Configuration** (No XML required)  
✅ **Spring Boot & Hibernate Integration**  

---

## 🛠️ Tech Stack
- **Backend:** Spring Boot, Spring Data JPA, Hibernate  
- **Database:** MySQL  
- **Build Tool:** Maven  
- **IDE:** Spring Tool Suite (STS) / IntelliJ IDEA  

---

## 📌 API Endpoints

### 🗂️ **Category CRUD APIs**
| Method | Endpoint                        | Description |
|--------|---------------------------------|-------------|
| `GET`  | `/api/categories?page=0`        | Get all categories (paginated) |
| `POST` | `/api/categories`               | Create a new category |
| `GET`  | `/api/categories/{id}`          | Get category by ID |
| `PUT`  | `/api/categories/{id}`          | Update category by ID |
| `DELETE` | `/api/categories/{id}`        | Delete category by ID |

### 🛒 **Product CRUD APIs**
| Method | Endpoint                        | Description |
|--------|---------------------------------|-------------|
| `GET`  | `/api/products?page=0`          | Get all products (paginated) |
| `POST` | `/api/products`                 | Create a new product |
| `GET`  | `/api/products/{id}`            | Get product by ID |
| `PUT`  | `/api/products/{id}`            | Update product by ID |
| `DELETE` | `/api/products/{id}`          | Delete product by ID |
  
---

## ⚙️ Setup & Installation
### 🛠 Prerequisites
- **Java 17+**
- **Spring Boot**
- **MySQL Database**
- **Maven**

### 🚀 Steps to Run
1️⃣ **Clone the Repository**
   ```sh
   git clone https://github.com/kavita3689/CategoryProductAPI.git
   cd CategoryProductAPI
