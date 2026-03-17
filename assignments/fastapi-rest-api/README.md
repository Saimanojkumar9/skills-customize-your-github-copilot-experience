# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Create a RESTful API using FastAPI that handles data operations with clear endpoints, validation, and auto-generated docs.

## 📝 Tasks

### 🛠️ 1. Build REST API Endpoints

#### Description

Use FastAPI to implement a simple data model and CRUD endpoints for an in-memory collection.

#### Requirements
Completed program should:

- Define at least one Pydantic model for request/response data
- Expose endpoints: `GET /items`, `GET /items/{id}`, `POST /items`, `PUT /items/{id}`, `DELETE /items/{id}`
- Handle errors for missing items with HTTP 404 responses
- Return appropriate HTTP statuses (e.g., 200, 201, 404)

### 🛠️ 2. Add validation and documentation

#### Description

Add input validation, clear response models, and use FastAPI docs features.

#### Requirements
Completed program should:

- Validate payload fields (e.g., required name, positive price) with Pydantic
- Use `response_model` for endpoint output shape
- Provide meaningful error messages for invalid input (HTTP 422)
- Verify API documentation is accessible at `/docs` and `/redoc`