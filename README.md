# Farmer Place

A farmer-to-consumer marketplace built with MongoDB, Express.js, React, and Node.js.

## Source and history

This repository imports [kisanbazar](https://github.com/ahadalireach/kisanbazar) at commit `00b0017b52f758a2e7d6af5afba2c91625e57ea4`.
The original source files, commit history, and author attribution are retained. The original documentation is available in [docs/UPSTREAM_README.md](docs/UPSTREAM_README.md).

The import and repository rename were prepared on 15 October 2026. The rename commit uses a user-requested historical date of 2026-09-15; that timestamp does not represent when this repository was created or when the upstream code was originally written.

## Stack

- Frontend: React, Redux Toolkit, Tailwind CSS, Vite
- Backend: Node.js, Express, Mongoose
- Database: MongoDB
- Authentication: JWT

## Run locally

1. Clone this repository and enter its directory.
2. In `api/`, run `npm install` and create a `.env` containing `PORT`, `MONGO_URI`, `JWT_SECRET`, and `JWT_EXPIRE`.
3. Run `npm run dev` in `api/`.
4. In `client/`, run `npm install` and create a `.env` containing `VITE_BACKEND_URL=http://localhost:5000`.
5. Run `npm run dev` in `client/` and open the Vite URL.

The application retains its original KisanBazar identifiers; Farmer Place is the repository name.
