# Progressive Web Apps - Complete Guide

This source code is part of Maximilian Schwarzmüller's "Progressive Web Apps - Complete Guide" course on udemy.com.

# How to Use

You need [Node.js](https://nodejs.org) installed on your machine. Simply download the installer from [nodejs.org](https://nodejs.org) and go through the installation steps.

Once Node.js is installed, open your command prompt or terminal and **navigate into this project folder**. There, run `npm install` to install all required dependencies.

Finally, run `npm start` to start the development server and visit [localhost:8080](http://localhost:8080) to see the running application.

# Add manifest.json

The manifest.json file is required for the Progressive Web App to work. It contains all the information about the app, such as the name, icons, theme color, and so on.

- How to configure the manifest.json file for chrome
- Adding Properties for Safari
- Adding Properties for the Internet Explorer

# Add service worker ( sw.js )

- Installing the service worker
- Activating the service worker
- Handling the fetch event

# Service worker:- caching

- Cache static assets in the service worker
- Cache dynamic assets in the service worker

# Service Workers - Advanced Caching

- Offering "Cache on Demand"
- Providing an Offline Fallback Page
- Strategy: Cache with Network Fallback
- Strategy: Cache Only
- Strategy: Network Only
- Strategy: Network with Cache Fallback
- Strategy: Cache then Network

# IndexedDB and Dynamic Data

- Understanding the Basics
- Setting Up Firebase
- Dynamic Caching vs. Caching Dynamic Content
- Introducing IndexedDB
- Storing Fetched Posts in IndexedDB
- Reading Data from IDB
- Deleting Single Items from the Database

# Creating a Responsive User Interface (UI)

- Understanding Responsive Design in our Project
- CSS and Media Queries
- Adding Animations

# Background Sync

- How does Background Sync Work?
- Registering a Synchronization Task
- Storing our Post in IndexedDB
- Syncing Data in the Service Worker
