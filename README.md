# Live Website: https://anime-season-v1.netlify.app/

## Overview

This project aims to provide a hands-on learning experience for mastering the diverse technologies involved in full-stack development, including Java Spring Boot for the backend, React for the frontend, and MongoDB for database management.

## Technologies Used

- **Backend: https://github.com/luisitocanlas/anime-backend**
  - Java Spring Boot
  - MongoDB

- **Frontend: https://github.com/luisitocanlas/anime-season-v1**
  - React

- **Development Tools:**
  - IntelliJ IDEA for Java
  - Visual Studio Code for React

## Deployment

### Frontend Deployment:

The React app is deployed on [Netlify](https://www.netlify.com/). The latest version of the app can be accessed [here](https://anime-season-v1.netlify.app/).

### Backend Deployment:

The backend is hosted using [Render Web Services](https://render.com/). The deployment utilizes a Docker image on Render.

## Limitations

### Render Free Tier Limitations:

#### Spinning down on idle
Render spins down a Free web service that goes 15 minutes without receiving inbound traffic. Render spins the service back up whenever it next receives a request to process.

Spinning up a service takes a few seconds, which causes a noticeable delay for incoming requests until the service is back up and running. For example, a browser page load will hang momentarily.
