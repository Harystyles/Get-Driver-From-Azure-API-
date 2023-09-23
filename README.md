# Get-Driver-From-Azure-API-

This repository holds a project that contains a basic Power Automate (formerly known as Microsoft Flow) that interacts with an API to fetch data based on a driver's ID input.

# Make an HTTP Request to Azure API

Add an action to make an HTTP request to your Azure API endpoint. Search for and select the "HTTP" action.
Configure the HTTP action with the following details:

## Method: GET
URI: The Azure API endpoint URL (including the necessary query parameters (e.g. Driver ID)).
Headers: API authentication, add the necessary headers (e.g., API key or bearer token).

## Parse the API Response

A JSON schema or use a sample response to generate the schema for the API response.
This helps Power Automate understand the structure of the data.
