LifeLink – Organ Management Platform
Overview

LifeLink is a web-based platform designed to streamline organ availability tracking and requests between procurement centres, transplant centres, and hospitals.
Instead of relying on manual methods like phone calls, faxes, or scattered spreadsheets, LifeLink enables real-time viewing of available organs and their details, ensuring faster decision-making when time is critical.

Prerequisites

Node.js and npm installed

A running MongoDB cluster, with its connection string stored in your system’s environment variables

Installation

From the project’s root directory, install dependencies for both the client and server:

cd client
npm install

cd ../server
npm install

Running the Application

Start the backend
From the server directory:

npm run start:dev


Start the frontend
From the client directory:

npm start


Open the app in your browser at:
http://localhost:3000/

Key Features

Displays real-time organ availability from multiple procurement and transplant centres in one dashboard.

Search and filter organs by attributes such as blood group or organ type.

Hospitals can request organs directly through the portal.

Integrated payment flow to confirm requests.

Procurement centres can approve or decline requests online.

Why LifeLink?

Organ transplants are highly time-sensitive, and delays in communication can mean the loss of a viable organ. LifeLink removes bottlenecks by providing a single platform for all participating centres, reducing manual work, errors, and delays.
