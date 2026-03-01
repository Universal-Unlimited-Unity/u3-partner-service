# U3 Partner Service

This is a **CRUD system** for **U3**, designed to manage and register **employees/partners**. You can add, update, delete, and view partner information through a simple web interface built with **Streamlit** and powered by a **FastAPI backend** connected to **PostgreSQL**.

## How to Run

1. **Clone the repository:**
```bash
git clone https://github.com/Universal-Unlimited-Unity/u3-partner-service.git

```


2. **Prerequisites:**
Make sure you have **Docker** and **Docker Compose** installed.
3. **Launch the application:**
Navigate into the project folder and run:
```bash
docker compose up --build

```


4. **Access the interface:**
Open your browser and go to:
`http://localhost:8501`
You’ll see the frontend where you can manage all partners and employees.

---

## Tech Stack & Features

* **Frontend:** Streamlit
* **Backend:** FastAPI with Pydantic
* **Database:** PostgreSQL with SQLAlchemy
* **Containerization:** Docker & Docker Compose

### Features:

* Add new partners/employees
* Update existing partner information
* Delete partners
* Search for individual or all partners
* Easy setup with Docker
