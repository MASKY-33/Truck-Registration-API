# Truck Registration API (FastAPI)
This project demonstrates how to build a simple backend API using FastAPI.
It introduces API endpoints, request handling, and in‑memory data storage.

# Purpose
The system registers trucks by their license plate and stores them in a live fleet list.
It shows how backend services receive data through HTTP requests and return structured responses.

## Features
- FastAPI application
- POST endpoint: /register-truck
- Accepts a truck’s license plate as input
- Stores all registered trucks in an in‑memory list
- Returns the updated fleet after each registration

## How it works
- A FastAPI app is created.
- An empty list live_feet acts as temporary storage.
- The endpoint /register-truck receives a license_plate parameter.
- The license plate is appended to the list.
- The API returns the full list of registered trucks.


## Learning Purpose
This project helps practice:
- Building API endpoints
- Understanding HTTP POST requests
- Managing in‑memory data
- Using FastAPI for backend development
- Returning JSON responses automatically
