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
    
    <img width="1595" height="877" alt="3000:users" src="https://github.com/user-attachments/assets/bb2b94dc-abf1-4ded-9a2b-aea3b72d2ed4" />


---

### **Product Service**
- **Base URL:** `http://localhost:3001`
- **Endpoints:**
  - **List Products:**  
    ```
    curl http://localhost:3001/products
    ```
    Or open in your browser: [http://localhost:3001/products](http://localhost:3001/products)

    <img width="1592" height="910" alt="3001:products" src="https://github.com/user-attachments/assets/de74391d-bf23-45f9-a49b-bd3404356af2" />


---

### **Order Service**
- **Base URL:** `http://localhost:3002`
- **Endpoints:**
  - **List Orders:**  
    ```
    curl http://localhost:3002/orders
    ```
    Or open in your browser: [http://localhost:3002/orders](http://localhost:3002/orders)

    <img width="1590" height="875" alt="3002:orders" src="https://github.com/user-attachments/assets/a06fd620-86c5-4ac3-aeac-5d4f59baa72a" />


---

### **Gateway Service**
- **Base URL:** `http://localhost:3003/api`
- **Endpoints:**
  - **Users:**  
    ```
    curl http://localhost:3003/api/users
    ```

    <img width="1590" height="876" alt="3003:api:users" src="https://github.com/user-attachments/assets/1b8096dd-7d7d-4dc6-8fce-1a27a9575642" />


  - **Products:**  
    ```
    curl http://localhost:3003/api/products
    ```

    <img width="1594" height="886" alt="3003:api:products" src="https://github.com/user-attachments/assets/7540e3c6-b9b9-4dcc-a9e7-58bd58644d88" />


  - **Orders:**  
    ```
    curl http://localhost:3003/api/orders
    ```

    <img width="1590" height="902" alt="3003:api:orders" src="https://github.com/user-attachments/assets/c720ebe2-01ff-47d5-a2aa-951aae87f7a7" />


---

## Instructions
1. Start all services using the `docker-compose` file:
   ```
   docker-compose up
   ```
2. Once the services are running, use the above endpoints to verify the functionality.

Happy testing!
