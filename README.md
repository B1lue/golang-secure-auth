# 🔐 Golang Secure Auth API

A secure authentication RESTful API built with:

- 🔑 JWT for stateless authentication
- 🔒 Bcrypt for password hashing
- 🐘 PostgreSQL (or MongoDB) as the database
- 🐳 Docker for containerization and easy deployment
- 🧼 Clean, scalable and security-focused architecture

---

## 🚀 Technologies Used

| Technology     | Purpose                                |
|----------------|-----------------------------------------|
| [Go](https://golang.org) | Main backend language              |
| [JWT](https://jwt.io)   | Stateless token authentication     |
| [Bcrypt](https://pkg.go.dev/golang.org/x/crypto/bcrypt) | Password encryption |
| [PostgreSQL](https://www.postgresql.org/) or [MongoDB](https://www.mongodb.com/) | Database |
| [Docker](https://www.docker.com/) | Containerization and orchestration |
| [Gin](https://github.com/gin-gonic/gin) | Web framework for building REST APIs |

---

## 🧪 API Endpoints

| Method | Endpoint     | Description                  | Auth Required |
|--------|--------------|------------------------------|----------------|
| POST   | `/register`  | Register a new user          | ❌              |
| POST   | `/login`     | Authenticate & return JWT    | ❌              |
| GET    | `/profile`   | Get user data by token       | ✅ (JWT)        |

---

## Create your .env file

PORT=8080
DB_USER=postgres
DB_PASSWORD=your_password
DB_NAME=secure_auth
DB_HOST=db
JWT_SECRET=your_super_secret_key

3. Run with Docker
docker-compose up --build

### 🔧 Environment Setup

#### 1. Clone the repository

```bash
git clone https://github.com/B1lue/golang-secure-auth.git



