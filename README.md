# Optimal Route Finder

This project utilizes Flask, Neo4j, Redis, and an external API to provide a optimal route finder for public transportation.

## Pre requisites

- Python 3.x
- Flask
- Neo4j
- APOC modlues in Neo4j
- Redis
- Haversine
- Requests

Install the required dependencies
Set up Neo4j and Redis on your local machine.
Update app.py with your Neo4j and Redis connection details.

## Usage:

Run the Flask application:
python app.py
Open your web browser and go to http://localhost:5000/.

Enter the start and end stations in the provided form and submit.
The application will find the route between the specified stations and display it.

## Features:

Finds the shortest route between two public transportation stations.
Utilizes Neo4j for storing station data and relationships between stations.
Uses Redis for caching station data to improve performance.
Incorporates Haversine formula for calculating distances between stations.
Provides a user-friendly web interface for interaction.

This is single use case of big project "Train Management System": https://github.com/Yamini-hari/Advanced-Databases-Team-NoSQL-Ninjas---Train-Tracking-System


