# Microservices-Task

## Overview
This document provides details on testing various services after running the `docker-compose` file. These services include User, Product, Order, and Gateway Services. Each service has its own endpoints for testing purposes.

---

## Services and Endpoints

### **User Service**
- **Base URL:** `http://localhost:3000`
- **Endpoints:**
  - **List Users:**  
    ```
    curl http://localhost:3000/users
    ```
    Or open in your browser: [http://localhost:3000/users](http://localhost:3000/users)

    ![alt text](<Screenshot 2026-09-20 at 20.41.52.png>)

---

### **Product Service**
- **Base URL:** `http://localhost:3001`
- **Endpoints:**
  - **List Products:**  
    ```
    curl http://localhost:3001/products
    ```
    Or open in your browser: [http://localhost:3001/products](http://localhost:3001/products)

    ![alt text](<Screenshot 2026-09-20 at 20.44.31.png>)

---

### **Order Service**
- **Base URL:** `http://localhost:3002`
- **Endpoints:**
  - **List Orders:**  
    ```
    curl http://localhost:3002/orders
    ```
    Or open in your browser: [http://localhost:3002/orders](http://localhost:3002/orders)

    ![alt text](<Screenshot 2026-09-20 at 20.46.17.png>)

---

### **Gateway Service**
- **Base URL:** `http://localhost:3003/api`
- **Endpoints:**
  - **Users:**  
    ```
    curl http://localhost:3003/api/users
    ```

    ![alt text](<Screenshot 2026-09-20 at 20.47.57.png>)

  - **Products:**  
    ```
    curl http://localhost:3003/api/products
    ```
    ![alt text](<Screenshot 2026-09-20 at 20.49.41.png>)

  - **Orders:**  
    ```
    curl http://localhost:3003/api/orders
    ```
    ![alt text](<Screenshot 2026-09-20 at 20.51.10.png>)

---

## Instructions
1. Start all services using the `docker-compose` file:
   ```
   docker-compose up
   ```
2. Once the services are running, use the above endpoints to verify the functionality.

Happy testing!
