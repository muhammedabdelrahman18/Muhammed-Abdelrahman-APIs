# 🏀 NBA APIs – Postman Collection

This repository contains a Postman collection featuring NBA-related APIs. Created and shared by **Muhammed Abdelrahman**, this collection allows you to fetch NBA teams, players, and match stats using a simple and clean interface.

---


## 🚀 Getting Started

### ✅ Prerequisites

- [Postman](https://www.postman.com/downloads/) installed on your machine
- Basic understanding of REST APIs and HTTP methods


## 📁 What's Inside

- `NBA APIs.postman_collection.json` — Postman collection with some requests such as :
  - Get all NBA teams
  - Get a specific team by ID
  - Get all players
  - Get a specific player by ID

---

## 📌 Some Requests

### 📥 1. Get LIST NBA Teams

- **Method:** `GET`  
- **URL:** `https://free-nba.p.rapidapi.com/teams`
- **Headers:**
  - `X-RapidAPI-Key: YOUR_API_KEY`
  - `X-RapidAPI-Host: free-nba.p.rapidapi.com`


**✅ Response:**

```json
{
 "data": [
{
    "id": 1,
    "name": "Atlanta Hawks",
    "nickname": "Hawks",
    "code": "ATL",
    "city": "Atlanta",
    "logo": "https://upload.wikimedia.org/wikipedia/fr/e/ee/Hawks_2016.png",
    "allStar": false,
    "nbaFranchise": true,
    "leagues": {
          "standard": {
                "conference": "East",
                "division": "Southeast"
                },
           "vegas": {
               "conference": "summer",
               "division": null
                },
           "utah": {
              "conference": "East",
              "division": "Southeast"
                },
           "sacramento": {
               "conference": "East",
               "division": "Southeast"
                }
            }
        },
    ...
  ]
}


### 📥 1. Get All NBA Teams

- **Method:** `GET`  
- **URL:** `https://free-nba.p.rapidapi.com/teams`
- **Headers:**
  - `X-RapidAPI-Key: YOUR_API_KEY`
  - `X-RapidAPI-Host: free-nba.p.rapidapi.com`
