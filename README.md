# dockerized-ecommerce-app
## Screenshots

### 1. Application Home Page
![App Home](screenshots/01-app-home.png)

The application is accessed through the EC2 public IP using Nginx reverse proxy.

---

### 2. Products Loaded from Backend and MySQL
![Products](screenshots/02-products-loaded.png)

Frontend fetches product data from backend API, which retrieves data from MySQL container.

---

### 3. API Response through Nginx
![API](screenshots/03-api-response.png)

The `/api/products` endpoint returns product data through the Nginx reverse proxy.

---

### 4. Running Docker Containers
![Docker PS](screenshots/04-docker-ps.png)

Shows all running containers: Nginx, frontend, backend, and MySQL.

---

### 5. Docker Compose Service Status
![Compose PS](screenshots/05-docker-compose-ps.png)

Displays service health status and container orchestration.

---

### 6. Docker Images
![Images](screenshots/06-docker-images.png)

Shows custom-built Docker images for frontend and backend.

---

### 7. Backend Logs
![Logs](screenshots/07-backend-logs.png)

Displays backend logs and successful API requests.

---

### 8. Project Structure
![Structure](screenshots/08-project-structure.png)

Shows organized project structure with all components.

---

### 9. AWS EC2 Instance
![EC2](screenshots/09-ec2-instance.png)

Shows EC2 instance running the application.

---

### 10. Security Group Rules
![Security](screenshots/10-security-group.png)

Shows inbound rules allowing HTTP and SSH access.
