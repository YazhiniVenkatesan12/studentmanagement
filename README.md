## 📘 Student Management Web Application

A web-based system for managing student records, built using **React.js** and **Firebase (Firestore + Authentication)**. This application allows admins to add, view, edit, and delete student details, as well as manage user authentication securely.

---
## 🌐 Live Website

🔗 [Click here to visit the Student Management System](https://student-management-e1305.web.app/)

---

## 🔐 Login Credentials

Use the following credentials to log in:

- **Email**: `admin@123.com`
- **Password**: `admin@123`

---
### 🚀 Features

* 🔐 **Firebase Authentication** for secure login/logout.
* 🧾 **Add, Edit, View, Delete** student details.
* 📄 Form includes:

  * Name
  * Class & Section
  * Roll Number
  * Email
  * Date of Birth
  * Phone & Guardian Details
  * Address
  * Hostel Type
  * Year of Admission
* 📁 Real-time data storage using **Firestore Database**.
* 🎨 Clean and responsive UI.

---

### 🛠️ Tech Stack

| Technology | Description          |
| ---------- | -------------------- |
| React.js   | Frontend framework   |
| Firebase   | Backend as a Service |
| Firestore  | NoSQL database       |
| CSS        | Styling and layout   |

---

### 🔧 Setup Instructions

1. **Clone the repository**:

   ```bash
   git clone https://github.com/YazhiniVenkatesan12/studentmanagement.git
   cd studentmanagement
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Set up Firebase**:

   * Go to [Firebase Console](https://console.firebase.google.com/).
   * Create a project.
   * Enable **Email/Password Authentication** in **Authentication > Sign-in method**.
   * Create a **Firestore Database**.
   * Copy your Firebase config and replace it in `firebase.js`.

4. **Run the app**:

   ```bash
   npm start
   ```

---

### 📁 Project Structure

```
student-management-app/
│
├── public/
├── src/
│   ├── components/
│   ├── firebase.js       # Firebase config
│   ├── App.js            # Main routing
│   ├── StudentsPage.js   # Main student form and table
│   └── App.css           # Styles
├── .gitignore
├── package.json
└── README.md
```

---

### 📸 Screenshots

> *(Optional – add screenshots of your UI here for a more visual README)*

---

### 🤝 Contribution

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

### 📄 License

This project is licensed under the MIT License.
[MIT License](https://choosealicense.com/licenses/mit/)

---

