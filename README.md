# ✅ Firebase Redux Todo App

A responsive, full-featured Todo application built with **React**, **Redux Toolkit**, and **Firebase Realtime Database**. Users can add, edit, mark as complete, and delete tasks — all with real-time updates.

---

## 🚀 Features

- 📦 Create, Read, Update, Delete (CRUD) todos  
- ⏱ Set task due dates and descriptions  
- ✅ Toggle task status between `pending` and `complete`  
- 🔄 Real-time updates using Firebase Realtime Database  
- ⚙️ Global state management using Redux Toolkit  
- 🎨 Clean UI with Bootstrap 5  

---

## 🧰 Tech Stack

- **Frontend:** React, Bootstrap 5  
- **State Management:** Redux Toolkit  
- **Backend:** Firebase Realtime Database  
- **HTTP Client:** Axios  

---

## 🛠️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/akshar51/Project-Firebase.git
cd Project-Firebase
```

### 2. Install dependencies
```bash
npm install
# or
yarn install
```

### 3. Firebase Setup
- Go to [Firebase Console](https://console.firebase.google.com/)
- Create a new project
- Go to **Project Settings > General > Web App Config**
- Create a `.env` file in the root and paste the following:

```env
VITE_FIREBASE_DATABASE_URL=https://your-database-name.firebaseio.com
```

Make sure your Realtime Database is in **test mode** or has appropriate read/write rules.

---

## 🔄 Available Scripts

### Start the development server
```bash
npm run dev
```

### Build the app for production
```bash
npm run build
```

### Preview the production build
```bash
npm run preview
```

---

## 📁 Project Structure

```
src/
├── api/
│   └── apiInstance.js         # Axios base instance
├── app/
│   └── store.js               # Redux store setup
├── features/
│   └── Todo/
│       ├── thunk.js           # Async thunks (CRUD)
│       └── todoSlice.js       # Redux slice
├── components/
│   └── TodoApp.jsx            # Main todo component
├── App.jsx                    # Entry point
└── main.jsx                   # React root + Provider
```

---

## 🧪 Core Functionality

- **Add Task:** Fill title, description, and due date then click "Add Task"  
- **Edit Task:** Click the ✏️ button next to a task  
- **Toggle Status:** Click ✅ or ↩️ to mark complete or pending  
- **Delete Task:** Click the 🗑️ button  

---

## ✨ UI Screenshots

*(Add screenshots here if desired)*

---

## 🙌 Acknowledgements

- [Firebase Realtime Database](https://firebase.google.com/docs/database)  
- [Redux Toolkit](https://redux-toolkit.js.org/)  
- [Bootstrap](https://getbootstrap.com/)  

---

## 📄 License

MIT License © 2025 [Akshar51](https://github.com/akshar51)

---

## 📬 Contact

If you have suggestions or issues, feel free to open an [Issue](https://github.com/akshar51/Project-Firebase/issues) or connect on GitHub.
