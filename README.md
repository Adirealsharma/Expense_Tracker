
```markdown
# 💸 Expense Tracker (Full Stack MERN App)

A full-featured Expense Tracker application built using the MERN stack (MongoDB, Express.js, React, Node.js). This app allows users to manage and visualize their personal expenses efficiently with a clean and responsive UI.

## 🚀 Features

- User registration and login (JWT-based authentication)
- Add, view, and delete expenses
- Categorized expense tracking
- Real-time transaction updates
- Monthly summary and filtering
- Responsive and mobile-friendly UI

## 🛠️ Tech Stack

- **Frontend:** React, Context API, Axios
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose)
- **Authentication:** JSON Web Tokens (JWT)
- **Styling:** CSS Modules / Tailwind CSS (if used)

---

## 📁 Project Structure

```

expense-tracker\_fullstack/
├── client/             # React frontend
├── server/             # Node.js + Express backend
├── .env.example        # Example environment variables
├── README.md           # Project documentation

````

---

## 🔧 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/Maclinz/expense-tracker_fullstack.git
cd expense-tracker_fullstack
````

---

### 2. Configure Environment Variables

Create a `.env` file in the `/server` directory using the `.env.example` as a template:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

### 3. Install Dependencies

#### Backend

```bash
cd server
npm install
npm run dev
```

#### Frontend

Open a new terminal window:

```bash
cd client
npm install
npm start
```

---

## 🌐 API Endpoints

### Auth Routes

| Method | Endpoint             | Description       |
| ------ | -------------------- | ----------------- |
| POST   | `/api/auth/login`    | Login user        |
| POST   | `/api/auth/register` | Register new user |

### Expense Routes

| Method | Endpoint            | Description       |
| ------ | ------------------- | ----------------- |
| GET    | `/api/expenses`     | Get all expenses  |
| POST   | `/api/expenses`     | Add new expense   |
| DELETE | `/api/expenses/:id` | Delete an expense |

---

## 📸 Screenshots

*Dashboard ![WhatsApp Image 2025-04-01 at 15 57 50_919b2f6d](https://github.com/user-attachments/assets/4c782334-11cf-4bed-891d-83485f882e18)
*
*Expenses ![WhatsApp Image 2025-04-01 at 15 57 50_19c8cfc1](https://github.com/user-attachments/assets/1a9c612e-e2b7-4551-877f-2e5c956ccfce)
*
*Incomes ![WhatsApp Image 2025-04-01 at 15 57 51_2d28bc5e](https://github.com/user-attachments/assets/1e7146ee-58a7-4481-8cd4-fdef3f426065)
*
---

## 🙌 Contributions

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---


```

---

Would you like me to generate badges (e.g., for build status, license, or tech stack) to include at the top?
```
