# Nuxt 3 Full-Stack Project

## 📌 Description

This is a **Full-Stack Nuxt 3** project using **Prisma, MySQL** for backend services. It provides CRUD operations for **Categories** and **Products**, including:

- Recursive Category Tree
- Image Upload (Stored Locally)
- Collapsible List UI for Categories
- Product Count in Categories
- Bootstrap + Vuetify for UI

## 🚀 How to Run the Project

### **1️⃣ Install Dependencies**

```sh
npm install
```

### **2️⃣ Configure Environment Variables**

Create a **.env** file in the root directory and add your MySQL connection details:

```ini
DATABASE_URL="mysql://user:password@localhost:3306/your_database"
```

### **3️⃣ Run Database Migrations**

```sh
npx prisma migrate dev --name init
```

### **4️⃣ Start the Development Server**

```sh
npm run dev
```

It will start the project at: `http://localhost:3000`

### **5️⃣ Start the Production Server**

```sh
npm run start
```

## 📌 Package.json Scripts

Ensure your **package.json** contains the necessary migration and build scripts:

```json
"scripts": {
  "dev": "nuxt dev",
  "build": "nuxt build",
  "start": "nuxt start",
  "migrate": "prisma migrate dev --name init",
  "migrate:prod": "prisma migrate deploy",
  "generate": "nuxt generate"
}
```

## 🛠 Tech Stack

- **Nuxt 3** - Frontend & Backend
- **Prisma** - ORM for MySQL
- **MySQL** - Database
- **Bootstrap & Vuetify** - UI Styling

✅ **Project is now ready to run!** Let me know if you need further refinements! 🚀
