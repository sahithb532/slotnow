

## 🚀 Project Setup Guide

### ✅ Prerequisites

- **Node.js**: [Download & Install](https://nodejs.org/)
- **MongoDB Community Server**: [Download & Install](https://www.mongodb.com/try/download/community)

During MongoDB installation:
- ✅ Select **Complete** setup
- ✅ Check **“Install MongoDB as a Service”**
- ✅ Check **“Add MongoDB to PATH”**

---

### 🛠️ Getting Started

#### 1. Start MongoDB

If installed as a service (default), open Command Prompt and run:

```bash
net start MongoDB
```

If not, create a data directory and start it manually:

```bash
mkdir C:\data\db
mongod --dbpath "C:\data\db"
```

---

#### 2. Set Up Backend

```bash
cd backend
npm install
```

---

#### 3. Seed the Database

Seeds the database with:
- An admin user
- Initial department data

```bash
node seed.js
```

---

#### 4. Start the Backend Server

```bash
npm start
```

---

### 🌐 Server Running At

```
http://localhost:5000
```

---




