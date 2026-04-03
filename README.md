# Patient CRUD System (FastAPI)

A RESTful API built using FastAPI to manage patient records with BMI calculation.

## 🚀 Features

* Create patient records
* Update patient details
* Delete patient
* View all patients
* Sort by BMI, height, weight

## 🛠 Tech Stack

* Python
* FastAPI
* Pydantic

## ▶️ Run Locally

```bash
uvicorn main:app --reload
```

## 📌 API Endpoints

* GET /view → View all patients
* POST /create → Create patient
* PUT /edit/{id} → Update patient
* DELETE /delete/{id} → Delete patient

## 📊 Special Feature

* Automatic BMI calculation with health verdict (Underweight, Normal, Overweight, Obese)
