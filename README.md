# AI-Powered Complaint Management Application

## Overview

This application helps users submit complaints with supporting camera photos and location information. It integrates Google Gemini for AI-powered assistance and Google Maps Platform for location-related functionality.

## Technologies Used

* **Google Gemini API:** AI-powered assistance.
* **Google Maps Platform API:** Map and location functionality.
* **Camera and Geolocation APIs:** Capture complaint evidence and its location.
* **Node.js and npm:** Local development environment.

## Prerequisites

* Node.js and npm
* Gemini API key
* Google Maps Platform API key

## Installation

1. Clone the repository.

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create `.env.local` using `.env.example`.

4. Configure your API keys.

5. Start the development server:

   ```bash
   npm run dev
   ```

## Privacy and Security

* Do not commit API keys or other secrets.
* Restrict Google Maps API keys to the required APIs and websites.
* Keep the Gemini API key on the server in production.
* Request camera and location permissions only when needed.
* Handle complaint photos and location data responsibly.

## Camera and Location Requirements

Complaint submission requires camera and location permissions. These browser features generally require localhost or an HTTPS connection.

## Pull Request

Please describe the changes, testing performed, and any relevant screenshots when submitting a pull request.
