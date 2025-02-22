# TrustLens

## Purpose
TrustLens is a professional website designed to build credibility and foster trust by showcasing key partners and collaborators. It highlights the contributions and services of partners through a dedicated 'Meet Our Partners' section, reinforcing transparency and reliability.

## Live URL
[Visit TrustLens](https://trust-lens.web.app/)


## Key Features
- **Meet Our Partners Section**: Features detailed partner information with logos, names, and descriptions.
- **Responsive Design**: Built for seamless performance across devices using TailwindCSS and daisyUI.
- **Modern UI/UX**: Sleek and visually appealing interface for a professional user experience.
- **React Components**: Modular components for easy development and scalability.

## Tech Stack
- **Frontend**: React.js, TailwindCSS, daisyUI
- **Icons**: React Icons


## npm Packages Used
- **React**: A JavaScript library for building user interfaces.
- **React DOM**: For rendering React components in the browser.
- **TailwindCSS**: A utility-first CSS framework for styling.
- **daisyUI**: A TailwindCSS-based library for pre-styled UI components.
- **React Icons**: For adding scalable vector icons.

## Dependencies
This project uses the following main dependencies:

- `axios`: ^1.7.9 - Promise-based HTTP client for the browser and Node.js.
- `firebase`: ^11.1.0 - Firebase SDK for integrating Firebase services.
- `react`: ^18.3.1 - A JavaScript library for building user interfaces.
- `react-dom`: ^18.3.1 - Serves as the entry point for DOM-related rendering paths in React.
- `react-router-dom`: ^7.1.1 - DOM bindings for React Router, enabling dynamic routing.
- `react-icons`: ^5.4.0 - Icon library for React with popular icons.
- `react-helmet-async`: ^2.0.5 - Manage changes to the document head in React.
- `sweetalert2`: ^11.15.3 - Beautiful, responsive, customizable replacement for JavaScript's alert.
- `swiper`: ^11.1.15 - A modern touch slider library.

## Dev Dependencies
For development purposes, the following dependencies are used:

- `eslint`: ^9.17.0 - A tool for identifying and reporting on patterns found in JavaScript code.
- `tailwindcss`: ^3.4.17 - Utility-first CSS framework.
- `vite`: ^6.0.5 - Next-generation, fast build tool and development server for modern web apps.


## Getting Started

Follow these steps to run the project on your local machine.

### Prerequisites

Before running this project, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (which includes npm)
- Git (if cloning the repository)

### Steps to Run Locally

1. **Clone the Repository**
   First, clone this repository to your local machine:

   git clone `https://github.com/Shifat507/TrustLens-website-client.git`
   cd `TrustLens-website-client`

2. **Install Dependencies**

    Next, install the project dependencies using npm:

    npm install
   
4. **Set Up Environment Variables**
   create a .env.local file and add firebase env variables and the base url.
   example:
    VITE_apiKey=----?----
    VITE_authDomain=----?----
    VITE_projectId=----?----
    VITE_storageBucket=----?----
    VITE_messagingSenderId=----?----
    VITE_appId=----?----

    VITE_URL=`https://trustlens-server-side.vercel.app`

5. **Run the Development Server**
    Start the development server by running the following command:

      npm run dev






