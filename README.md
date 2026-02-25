# ShopSmart-Your-Digital-Grocery-Store-Experience(Fullstack)

ShopSmart is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) e-commerce web application designed to provide a convenient and efficient online grocery shopping experience. It allows users to browse products, manage their cart, place orders, and enables administrators to manage products, users, and orders.

This repository contains the full ShopSmart project with Backend and Frontend folders.

Overview
- Backend: Node/Express app located in `code/Backend` (uses MongoDB).
- Frontend: React app (Create React App) located in `code/Frontend`.

Quick start (local)

Prerequisites
- Node.js (v16+ recommended)
- npm
- MongoDB running locally on default port (27017) or change the connection string in `code/Backend/db/connect.js`

Run backend
```powershell
cd 'c:\Users\karth\OneDrive\Desktop\ShopSmart\code\Backend'
npm install
npm run dev   # starts nodemon index.js
# or: npm start   # runs node index.js
```

Run frontend
```powershell
cd 'c:\Users\karth\OneDrive\Desktop\ShopSmart\code\Frontend'
npm install
npm start
```

Default ports
- Frontend (dev): http://localhost:3000
- Backend API: http://localhost:5100

Notes
- The backend currently uses an in-repo DB URI: `mongodb://127.0.0.1:27017/grocery` (see `code/Backend/db/connect.js`).
- Move secrets (JWT keys, DB URI) to environment variables before deploying.

Git / GitHub
- To push this repository to GitHub, create a remote repository and run:
```powershell
cd 'c:\Users\karth\OneDrive\Desktop\ShopSmart\code'
# example (replace URL):
# git remote add origin https://github.com/<your-username>/<repo-name>.git
# git push -u origin main
```

Or, if you have the GitHub CLI installed:
```powershell
cd 'c:\Users\karth\OneDrive\Desktop\ShopSmart\code'
# interactive create and push:
# gh repo create <repo-name> --public --source=. --remote=origin --push
```

If you'd like, I can also create the GitHub repo for you — provide a Personal Access Token (PAT) with `repo` scope, or create the remote yourself and share the URL and I'll finish the push from here.

Contact / next steps
- Tell me if you want me to create the remote repo for you (and whether to make it public/private). If yes, either run the `gh repo create` command yourself or provide a PAT and the desired repo name and visibility and I will create it and push.
