# Azure Web Application

A Python Flask web application designed to demonstrate web application development and deployment using Microsoft Azure App Service.

## Technologies Used

- Python
- Flask
- Microsoft Azure App Service
- Git
- GitHub

## Application Endpoints

### /

Displays the main web application page.

### /health

Returns the health status of the application.

Example response:

```json
{
  "status": "healthy",
  "application": "azure-web-application"
}

