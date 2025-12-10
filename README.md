# Live City Search (original)

A small JavaScript-based web application created during my *JavaScript* module.  
This project focuses on API handling, dynamic UI updates, and implementing a live search function.

**Module:** JavaScript  
**Goal:** Working with Web APIs & real-time search  
**Status:** ✅ Completed  
**Version:** 1.0  
**Tech:** JavaScript, Bulma CSS  

---

## 📌 Project Overview

The task was to build a simple web app with four input fields:

- **City**  
- **ZIP Code** (readonly)  
- **Longitude** (readonly)  
- **Latitude** (readonly)

As the user types, the app fetches city suggestions from a public Web API and displays them in a dropdown list.  
Selecting a suggestion automatically fills in the ZIP code.  
Using that ZIP code, a second API request retrieves the corresponding longitude and latitude values.

The project focuses on asynchronous JavaScript, DOM updates, and integrating multiple API responses.

---

## ✨ Features

- Live city search with dynamic suggestions  
- Automatic ZIP code fill-in based on selected city  
- Fetching longitude and latitude via external API  
- Clean and responsive UI with Bulma  
- Real-time updates without reloading the page  

---

## 🧠 What I Learned

- How to work with the `fetch()` API in JavaScript  
- Handling asynchronous operations and JSON data  
- Updating the DOM dynamically based on user input  
- Debouncing live search inputs  
- Basic error handling for API calls  
- Designing small interactive features without frameworks  

This was my first project involving real Web APIs and gave me a clear understanding of how frontend logic communicates with external data sources.

