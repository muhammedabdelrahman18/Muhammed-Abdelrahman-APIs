# 🏀 NBA APIs – Postman Collection

This collection allows you to fetch NBA teams, players, games and match stats using a simple and clean interface.

<img width="299" height="254" alt="NBA Categories" src="https://github.com/user-attachments/assets/47dc2ceb-9a97-4aff-ae50-6ee75ba8088f" />
<img width="1366" height="768" alt="Collection Scripts" src="https://github.com/user-attachments/assets/0e914440-bd2f-477e-bb95-9f164e304246" />




---


### ✅ Prerequisites

- [Postman](https://www.postman.com/downloads/) installed on your machine


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
  ]
}

```
<img width="1366" height="768" alt="request1 test script" src="https://github.com/user-attachments/assets/b9ccd110-c995-4f62-9f3b-73bdaf2bfba0" />


### 📥 2. Get Team by CODE


**Request:**

- **Method:** `GET`
-  GET https://free-nba.p.rapidapi.com/teams?code=ATL


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
<img width="1366" height="768" alt="request2 test script" src="https://github.com/user-attachments/assets/981f6216-bd83-42db-a41c-738b5c7a95ce" />


### 🧑‍💻 Author

**Muhammed Abdelrahman**

GitHub: [@muhammedabdelrahman18](https://github.com/muhammedabdelrahman18)


