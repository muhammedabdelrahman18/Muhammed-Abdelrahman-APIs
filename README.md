# 🏀 NBA APIs – Postman Collection

This collection allows you to fetch NBA teams, players, games and match stats using a simple and clean interface.

---


## 🚀 Getting Started

### ✅ Prerequisites

- [Postman](https://www.postman.com/downloads/) installed on your machine
- Basic understanding of REST APIs and HTTP methods


## 📁 What's Inside

- `NBA APIs.postman_collection.json` — Postman collection with requests such as :
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


**✅ Sample Response:**

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

```
### 📥 2. Get Team by CODE

- **Method:** `GET`  
- **URL:** `https://free-nba.p.rapidapi.com/teams/{team_id}`  
- Replace `{team_id}` with an actual team ID (e.g., `14` for Los Angeles Lakers).

### ✅ Example

**Request:**

GET https://free-nba.p.rapidapi.com/teams?code=ATL

**Required Headers:**

X-RapidAPI-Key: YOUR_API_KEY
X-RapidAPI-Host: free-nba.p.rapidapi.com


**✅ Sample Response:**

```json
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

```
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/53e0d02f-92a6-4001-9218-a3782ee2dde6" />

### 🧑‍💻 Author

**Muhammed Abdelrahman**

GitHub: [@muhammedabdelrahman18](https://github.com/muhammedabdelrahman18)
