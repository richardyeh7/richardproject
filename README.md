# Traffic-Based Restaurant Recommendation

A web application that recommends restaurants along your driving route, considering **live traffic, timing constraints, and restaurant ratings**.  
Built with Google Maps APIs, this project demonstrates full-stack problem solving, API integration, and user-centric design.

---

## Problem
Drivers often want to stop for food but don’t know **which restaurants fit their schedule** without risking delays. Existing apps don’t integrate both *traffic conditions* and *stay duration* into recommendations.

---

## Approach
- **Google Maps Directions API**: Calculate routes and split them into segments.  
- **Google Places API**: Query nearby restaurants along eligible segments.  
- **Filtering logic**: Only show restaurants with rating ≥ 4.0, within the user’s available time window.  
- **Custom scoring**: Evaluate “time difference” (detour vs direct route) to rank the best options.  
- **Dynamic UI**: Display route, markers, and restaurant info with photos and ratings.

---

## Features
- Enter start/end points, departure, and time constraints.  
- Automatically suggest the **top 10 restaurants** that best fit your trip.  
- Display restaurant name, rating, address, ETA, and detour cost.  
- Interactive map with markers for each recommended stop.  
- Supports configurable stay duration.

---

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **APIs:** Google Maps Directions, Places, Geometry  
- **Libraries:** Google Maps JS SDK  
- **Deployment:** GitHub Pages / Static hosting  

