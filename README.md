# TBKEE Home Service Finder Application

A full-stack platform connecting households with domestic workers, optimizing job matching for home services. The system enables customers to book and manage cleaning services while empowering workers with job opportunities.

## 🏗 Project Structure

This repository is organized as a **monorepo** with separate directories for frontend, backend, and admin panel:

TBKEE-Platform/ │── fe/ # Frontend (React Native) │── be/ # Backend (Node.js, MongoDB) │── admin/ # Admin Panel (TypeScript) │── README.md │── .gitignore

markdown
Sao chép
Chỉnh sửa

## 🚀 Features
✅ **Customers**
- Search and book home services (cleaning, housekeeping, etc.).
- Track job status, payments, and service history.
- Rate and review workers.

✅ **Workers**
- Receive and manage job requests.
- Update job progress (in-progress, completed).
- Monitor earnings and job history.

✅ **Admin Panel**
- Manage user accounts (customers & workers).
- Oversee service requests and transactions.
- Generate reports and analytics.

## 🛠 Tech Stack

| Layer        | Technology                          |
|-------------|------------------------------------|
| **Backend**  | Node.js, Express.js, MongoDB      |
| **Frontend** | React Native                      |
| **Admin**    | TypeScript, React                 |
| **Other**    | GoongMap API (Location Services)  |

## 🏗 Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/TBKEE-Platform.git
cd TBKEE-Platform
2️⃣ Install dependencies for each service
bash
cd be && npm install   # Backend
cd ../fe && npm install   # Frontend
cd ../admin && npm install   # Admin Panel
3️⃣ Set up environment variables
Create a .env file inside each directory (be/, fe/, admin/) and configure settings like database URL, API keys, etc.

4️⃣ Run the application
Backend
bash
cd be
npm start
Frontend (React Native)
bash
cd fe
npx react-native run-android  # For Android
npx react-native run-ios      # For iOS
Admin Panel
bash
cd admin
npm start
📌 API Documentation
The backend follows RESTful API principles. API documentation is available in the be/docs/ folder.

📌 Contributing
Fork this repository.
Create a new branch (feature/new-feature).
Commit your changes (git commit -m "Added new feature").
Push to the branch (git push origin feature/new-feature).
Open a Pull Request.
🔥 Future Improvements
Implement AI-based job recommendations.
Add real-time chat between customers and workers.
Improve analytics dashboard for admins.
👨‍💻 Authors
Your Name – Backend & API Development
Your Teammate – Frontend Development
Your Teammate – Admin Panel Development
