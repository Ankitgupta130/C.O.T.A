# C.O.T.A (Colonizing Online Till Anywhere)

C.O.T.A is an innovative online platform that redefines the way people find and book accommodations. Whether you're looking for a short stay, a few hours of rest, or a long-term paying guest (PG) arrangement, C.O.T.A offers flexible and convenient options tailored to your needs.

Our mission is to make accommodation accessible and adaptable for everyone, everywhere. From hourly bookings to budget-friendly PGs, C.O.T.A empowers users to explore, compare, and book spaces with ease, bridging the gap between travelers, students, professionals, and property owners.

With a user-friendly interface and a focus on transparency, C.O.T.A ensures a seamless experience for both hosts and guests, providing a trusted ecosystem for affordable and flexible stays. Whether you're in a new city or just need a short-term space, C.O.T.A has you covered.

---

## Table of Contents
- [Features](#features)  
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Installation ](#installation)
- [Project Structure](project-structure)
---

## Features
- **Flexible Booking Options**:  
  Book accommodations on an hourly basis or choose long-term PG arrangements.  

- **Real-Time Updates**:  
  Availability of rooms and bookings is synced in real-time using Firebase Realtime Database.  

- **User Authentication**:  
  Secure and reliable authentication system powered by Firebase and Auth0, supporting multiple login methods (email, Google, etc.).  

- **Search and Explore**:  
  Easy-to-use search functionality to find accommodations that meet your preferences and budget.  

- **Seamless User Experience**:  
  A modern React.js frontend ensures a smooth and responsive interface for users on all devices.  

- **Host and Guest Features**:  
  Hosts can list and manage their spaces, while guests can explore and book with ease.  

---

## Tech Stack
- **React.js**: Frontend framework for building a dynamic, responsive, and user-friendly interface.  
- **Firebase**:  
  - **Authentication**: Secure user login and registration.  
  - **Realtime Database**: Instant updates for accommodation availability and bookings.  
- **Auth0**: Authentication and authorization for secure and scalable user access management.  

---

## Getting Started

### Prerequisites
- Node.js and npm installed
- Firebase account for configuration
- Auth0 account for managing authentication  

### Installation
1. Clone the repository:  
   ```bash
   git clone https://github.com/KaustubhPatil02/C.O.T.A.git
   ```
   cd cota
   
2. Install Dependencies:
   ```
   npm i
   ```

3. Set up Firebase:

  - Create a Firebase project on the Firebase Console.
  - Enable Authentication and Realtime Database in the Firebase project.
  - Add your Firebase configuration to the project.

4. Set up Auth0:

  - Create an Auth0 application on the Auth0 Dashboard.
  - Configure Auth0 to support your login methods (e.g., email, Google).
  - Add your Auth0 configuration to the project.

5. Start the development server:
   ```
    npm start
   ```
   ---
### Project Structure:

