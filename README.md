# ethereum-lite-explorer-backend

## Description

This project is an open-source block explorer on EVM chain. If you follow this repository, you can run explorer in localhost. This repository provides backend code. This server uses a RESTful API to access the database and fetch data.

## Getting Started

### Installing

- If you have not built a crawling server, please follow the link below first.

  - <https://github.com/Generation-Foundation/ethereum-lite-explorer-crawling>

- Git clone this repo

```bash
git clone https://github.com/Generation-Foundation/ethereum-lite-explorer-back.git
```

- Create `.env` to update MySQL database settings.

```env
DB_HOST="host"
DB_USER="user"
DB_PASSWORD="password"
DB_DATABASE="explorer_db"
```

- Run it local with the following command

```bash
npm install --save
node server.js
```
