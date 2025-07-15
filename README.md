# NewsMania

Welcome to **NewsMania**, a web application designed to keep you updated with the top business news headlines fetched from sources like Times of India and others using the https://newsapi.org. This project utilizes a combination of backend middleware and direct API calls. The middleware, built with Express.js, handles some API requests, while others are fetched directly from the frontend via the github API to fetch the admin information directly from Github account. The application also integrates Google authentication for seamless login and logout, and leverages Web3 forms to trigger emails to the admin.

## Features

- **Business News Headlines**: Fetches top business Headlines from sources like Times of India and others via NEWSAPI.
- **Google Authentication**: Integrates Google login/logout for user authentication.
- **Github API**: Fetches user data from Github.
- **Web Forms Integration**: Sends emails to the admin using Web forms.

## Middleware Explanation

NEWSAPI allows fetching data from their API on localhost only. However, CORS (Cross-Origin Resource Sharing) are blocked for any other production deployment. To bypass these CORS restrictions, a middleware is created using Express.js. This middleware resolves the CORS issues by fetching the data at the backend and displaying it on the frontend.


## Technologies Used

- **Frontend**:
  - React + Vite
  - Tailwind CSS
  - React Router DOM
  - GSAP(GreenSock Animation Platform)

- **Backend**:
  - Express.js (as middleware/proxy server)
  - Firebase (for authentication)
  - Railway.app (for hosting backend)

- **APIs**:
  - NEWSAPI (for fetching news)
  - Github API (for fetching user data)
  - Google Authentication (for user login/logout)
  - Web3Forms (for handling web forms and email triggers)

- **Deployment**:
  - Vercel (for deploying frontend)
  - Railway.app (for deploying backend)



  
  



