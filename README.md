# Microservices Containerization Assessment

A containerized Node.js microservices architecture orchestrated using Docker and Docker Compose.

---

## 🏗️ Architecture Overview

The system consists of four containerized microservices communicating over an internal Docker bridge network (`microservices-network`):

* **User Service** (`port 3000`): Manages user identity and accounts.
* **Product Service** (`port 3001`): Provides catalog data and product listings.
* **Order Service** (`port 3002`): Manages customer purchase orders.
* **Gateway Service** (`port 3003`): Reverse proxy and central API entry point routing requests to internal microservices via container DNS.

---

## ⚙️ Prerequisites

* [Docker Engine](https://docs.docker.com/engine/install/) (v20.10 or higher)
* [Docker Compose](https://docs.docker.com/compose/) (v2.0 or higher)

---

## 🚀 Setup & Execution Instructions

1. **Clone the Forked Repository:**
   ```bash
   git clone [https://github.com/Atulpatilll/Microservices-Task.git](https://github.com/Atulpatilll/Microservices-Task.git)
   cd Microservices-Task
