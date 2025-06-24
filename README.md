# FinTrack - Personal Expense Manager 💰

A modern, full-stack Expense Management web application built using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js) and **Ant Design** for an intuitive and responsive user interface.

---

## ✨ Key Features

- ➕ **Add, Edit & Delete Transactions**  
- 📅 **Filter Transactions by Date**
- 🔄 **Filter by Type (Income / Expense)**
- 📊 **Comprehensive Analysis of Earnings vs. Expenses**
- 🏷️ **Categorical Breakdown of Income and Expense Types**
- 🔐 **User Authentication (Login / Logout)**
- ⚡ **Dynamic Updates without Page Reload (SPA)**
- 📱 **Responsive Design with Ant Design Components**

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/guptasamarth200/FinTrack.git
cd FinTrack
```
### 2. Configure Environment Variables
## Create a .env file in the root directory and add the following:
```bash
NODE_ENV=development
PORT=5000
MONGO_URI=your_mongodb_connection_string
```
### 3. Install Dependencies
## Install backend dependencies
```bash
npm install
```

### Move to frontend and install dependencies
```bash
cd frontend
npm install
```
4. Run the Application
### Run both frontend (on :3000) & backend (on :5000)
```bash
npm run start
```
## Run Backend Only
```bash
node server.js
```
#### 🔧 Build & Deployment
## To create a production build for deployment:
```bash
cd frontend
npm run build
```
### Heroku Deployment Note:
### A postbuild script is included, so no need to manually build the frontend when deploying to Heroku.

### 🛠️ Tech Stack
```bash 
Frontend: React.js, Ant Design

Backend: Node.js, Express.js

Database: MongoDB

State Management: React Context API / useReducer

Authentication: JWT (JSON Web Tokens)

Environment Management: dotenv

Deployment: Heroku (or any cloud platform)
```

### 💡 Notes
Uses ES Modules in the backend — requires Node v14.6+

When importing files (not packages), make sure to include the .js extension

Babel setup can be added optionally if needed

### 🤝 Contributing
Contributions are welcome!
Feel free to open an issue or submit a pull request.
