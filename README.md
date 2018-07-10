# bnk48-json-server
A full fake REST API
  - based on https://github.com/typicode/json-server
  - data from https://www.bnk48.com/#/members

## Preparation
  - `npm install -g json-server`

## How to use ?
  - `json-server --watch bnk48-db.json`
  - go to `http://localhost:3000/members`

## Simple methods
  - GET    /members
  - GET    /members/2
  - POST   /members      // example { "id": 100, "slug": "aoffy"  }
  - PUT    /members/2
  - PATCH  /members/2
  - DELETE /members/2

** when use POST/PUT/PATCH/DELETE methods json file is will update too. **
