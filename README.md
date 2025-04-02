# TO-DO LIST APP

## 📌 Overview
This is a **responsive To-Do List App** built using **React** and **Vite** with the **Context API** for state management. It allows users to **add, edit, delete, and mark tasks as complete** while maintaining **localStorage persistence** to retain tasks even after a page refresh.

## 🚀 Features
- ✅ **Add new tasks**
- 📝 **Edit existing tasks**
- ❌ **Delete tasks**
- 🎯 **Mark tasks as completed**
- 🔄 **State persistence using localStorage**
- 🎨 **Fully responsive design** with Tailwind CSS
- ⚡ **Optimized with Vite for fast performance**

## 🏗️ Technologies Used
- **React (Vite)** – Frontend Framework
- **Context API** – State Management
- **Tailwind CSS** – Styling
- **LocalStorage** – Data Persistence

## 📂 Folder Structure
```
TO-Do-List/
│── public/                 # Static files
│── src/
│   ├── components/         # Reusable components
│   │   ├── TodoForm.jsx    # Form to add a new task
│   │   ├── TodoItem.jsx    # Individual task item
│   ├── contexts/
│   │   ├── TodoContext.jsx # Context API for state management
│   ├── App.jsx             # Main Application file
│   ├── main.jsx            # React entry point
│── .gitignore              # Files to ignore in version control
│── index.html              # Main HTML file
│── package.json            # Project dependencies
│── tailwind.config.js      # Tailwind CSS configuration
│── vite.config.js          # Vite configuration
```

## ⚡ Installation & Setup
1. **Clone the repository**
   ```sh
   git clone https://github.com/Vishallokhande8788/TO-Do-List.git
   cd TO-Do-List
   ```
2. **Install dependencies**
   ```sh
   pnpm install
   ```
3. **Start the development server**
   ```sh
   pnpm run dev
   ```
4. **Open the app in the browser**  
   Vite will display a local development URL (e.g., `http://localhost:5173`).

## 🛠️ Deployment (Cloudflare Pages)
To deploy this app on **Cloudflare Pages**:
1. Push your project to **GitHub**.
2. Go to **Cloudflare Pages** → **Create a Project**.
3. Select the repository and configure it:
   - **Build command:** `npm run build`
   - **Output directory:** `dist`
   - **Framework preset:** `React (Vite)`
4. Click **Deploy** and wait for the process to complete.

Your deployed app will be live at:  
🔗 **[https://to-do-list-88e.pages.dev/](https://to-do-list-88e.pages.dev/)**

## 💡 Future Improvements
- 🌐 Add **backend integration** for authentication
- 📅 Implement **due dates** and **task reminders**
- 📊 Add **task analytics** (completed vs pending)
- 🎭 Improve UI with animations

## 👨‍💻 Author
**Vishal Lokhande** – Full Stack Devloper

🚀 Happy Coding! 🎯

