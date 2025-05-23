﻿# Xohani-Assignment
 This is the frontend implementation of a webinar management platform developed using React. The application allows users to view available webinars, see detailed information about specific webinars, and create new webinars.

## Project Structure


Xohani-Assignemnt /
├── dist/
├── node_modules/
├── public/
├── src/
│   ├── assets/
│   ├── Component/
│   │   ├── Button.jsx
│   │   ├── Card.jsx
│   │   ├── CardContent.jsx
│   │   ├── CreateWebinar.jsx
│   │   ├── Dashboard.jsx
│   │   ├── Home.jsx
│   │   ├── Toast.jsx
│   │   ├── WebinarConfirmation.jsx
│   │   └── WebinarDetails.jsx
│   ├── context/
│   │   └── WebinarContext.jsx
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── .eslintrc.js
├── .gitignore
├── index.html
├── package-lock.json
├── package.json
└── README.md


## Features

The frontend application consists of three main screens:

1. *Webinar Listing Page (Home.jsx)* - Displays all available webinars in a card format
2. *Webinar Detail Page (WebinarDetails.jsx)* - Shows comprehensive information about a specific webinar
3. *Webinar Creation Page (CreateWebinar.jsx)* - Allows users to create a new webinar

## Setup and Installation

1. Clone the repository:
   bash
   git clone <repository-url>
   cd Xohani-Assignemnt 
   

2. Install dependencies:
   bash
   npm install
   

3. Start the development server:
   bash
   npm run dev
   

4. The application will be available at http://localhost:5173 (or the port specified in your configuration)

## Component Overview

### Main Components

- *Home.jsx*: The landing page displaying all webinars
- *WebinarDetails.jsx*: Detailed view of a specific webinar
- *CreateWebinar.jsx*: Form for creating new webinars
- *WebinarConfirmation.jsx*: Confirmation page after webinar creation
- *Dashboard.jsx*: Admin dashboard for webinar management

### Utility Components

- *Button.jsx*: Reusable button component
- *Card.jsx*: Container component for displaying webinar cards
- *CardContent.jsx*: Content layout for individual webinar information
- *Toast.jsx*: Notification component for user feedback

### Context

- *WebinarContext.jsx*: Provides state management for webinar data across components

## API Integration

The frontend uses API calls to fetch and manage webinar data. Currently, mock data is implemented as per requirements. The API integration points include:

- Fetching all webinars (GET)
- Fetching a specific webinar (GET)
- Creating a new webinar (POST)

## Design Implementation

The UI is implemented according to the provided Figma designs with a focus on:

- Pixel-perfect implementation of design specifications
- Responsive layout
- Clean and structured UI
- Intuitive user experience

## Technologies Used

- React
- CSS/SCSS for styling
- Context API for state management
- Fetch/Axios for API calls

## Development Notes

- The application uses mock data where applicable for development purposes
- API calls are structured to be easily replaced with actual backend endpoints
- The UI is responsive and adapts to different screen sizes

## Future Improvements

- Implement authentication
- Add filtering and search functionality
- Enhance responsive design for mobile experiences
- Implement real-time updates for webinar status
