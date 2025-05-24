Weather Dashboard

https://github.com/Pricilla-Francis/Weather-Dashboard.git


# User Story
AS A traveler
I WANT to see the weather outlook for multiple cities
SO THAT I can plan a trip accordingly


# Acceptance Criteria
GIVEN a weather dashboard with form inputs
WHEN I search for a city
THEN I am presented with current and future conditions for that city, and that city is added to the search history
WHEN I view current weather conditions for that city
THEN I am presented with the city name, the date, an icon representation of weather conditions, a description of the weather for the icon's `alt` tag, the temperature, the humidity, and the wind speed
WHEN I view future weather conditions for that city
THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, the wind speed, and the humidity
WHEN I click on a city in the search history
THEN I am again presented with current and future conditions for that city

# GitHub Actions CI/CD Setup

This repository demonstrates a complete CI/CD (Continuous Integration / Continuous Deployment) workflow using **GitHub Actions**. It includes automated testing, linting, build, and deployment steps, and can be adapted to suit various project types (e.g., Node.js, React, Python, Docker, etc.).


# Features

Automated testing on every push and pull request
Code linting to enforce style consistency
Build pipeline with artifact uploads
Deployment to environments like GitHub Pages, Render, or Vercel
Branch-specific workflows (e.g., only deploy `main`)
Secrets management via GitHub

