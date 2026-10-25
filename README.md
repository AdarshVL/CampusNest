# 🏫 Mess & Hostel Info App 🍲

# 🌐 CampusNest - Smart Mess & Hostel Information System 

CampusConnect is a **personalized web application** designed for **students, hostel/PG owners, and mess providers**.  
It centralizes information like **mess charges, daily menus, room rents, facilities, photos, and direct contacts**,  
making student life simpler and management smarter.

---

## 🚀 Overview

Every student faces challenges finding affordable, quality food and rooms near their campus.  
**CampusConnect** bridges this gap by building a digital ecosystem where:

- Students can discover messes, compare charges, and view menus.
- Hostel/PG owners can showcase available rooms, facilities, and pricing.
- The platform fosters **transparent, real-time communication** between both sides.

---
## 🧩 Features

### 🎓 For Students
- Browse verified **mess and hostel details**.
- Check **daily/weekly menus** and **ratings**.
- Compare **room rents**, facilities, and pictures.
- Directly **contact owners** for booking or queries.

### 🏠 For Owners/Admins
- Add or update mess menus and prices.
- Upload room information with rent, facilities, and availability.
- View feedback and inquiries from students.
- Manage listings with an intuitive dashboard.

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
|-------|-------------|----------|
| **Frontend** | React.js + Tailwind CSS | Responsive user interface |
| **Backend** | Node.js + Express.js | RESTful API development |
| **Database** | MongoDB (or MySQL) | Data storage for users, messes, rooms |
| **Containerization** | Docker | Build and run app in isolated environments |
| **Reverse Proxy** | NGINX | Route requests to frontend and backend |
| **Deployment** | Render / Railway / Vercel | Cloud hosting and scalability |
| **CI/CD** | GitHub Actions | Automated testing and deployment pipeline |

---

## 📂 Dataset
A sample dataset is included: [View Dataset](https://github.com/AdarshVL/Mess_Hostel_Info_App/blob/main/mess_hostel_dataset.csv)

This dataset includes:

| Field | Description |
|-------|--------------|
| Mess_Name | Name of the mess or food provider |
| Location | Area or proximity to campus |
| Daily_Menu | Food items offered daily |
| Monthly_Charges(INR) | Monthly cost for meals |
| Quality_Rating(1-5) | Based on feedback |
| Room_Type | Type (Single, Double, Triple sharing) |
| Monthly_Rent(INR) | Cost of room per month |
| Facilities | Amenities (WiFi, Laundry, etc.) |
| Owner_Contact | Owner’s contact number |
| Pictures_Link | Image URLs of rooms/mess |

---
## 📂 Project Structure
```
CampusConnect/
│
├── client/ # React frontend
│ ├── src/
│ ├── public/
│ └── package.json
│
├── server/ # Node.js + Express backend
│ ├── routes/
│ ├── models/
│ ├── controllers/
│ └── server.js
│
├── data/ # Datasets & Seed Data
│ └── mess_hostel_dataset.csv
│
├── docker-compose.yml # Multi-container configuration
├── Dockerfile # Container setup
├── nginx.conf # Reverse proxy configuration
├── .github/workflows/ # CI/CD pipeline (GitHub Actions)
│
└── README.md
```
----

## 🌍 Deployment Options

| Platform           | Use Case                      | Link                                                      |
| ------------------ | ----------------------------- | --------------------------------------------------------- |
| **Render**         | Free tier for backend hosting | [https://render.com](https://render.com)                  |
| **Railway**        | Full-stack deploys (DB + API) | [https://railway.app](https://railway.app)                |
| **Vercel**         | Frontend (React) deployment   | [https://vercel.com](https://vercel.com)                  |
| **GitHub Actions** | CI/CD automation              | [GitHub Actions Docs](https://docs.github.com/en/actions) |

---
 
## 👨‍💻 Future Enhancements

🔐 JWT-based authentication (Student/Admin)

💳 Online mess/room booking with Razorpay integration

🧾 Feedback and rating system

📊 Analytics dashboard for owners

☁️ Cloud-hosted image uploads (Cloudinary / AWS S3)

---

## 💡 Example Use Case

### 🎓 The Student:

✔ A new student joins college and wants to:

✔ View nearby hostels and messes with pricing.

✔ Compare quality, pictures, and food variety.

✔ Contact the owner and book directly.

### 🏠 Meanwhile, the owner:

✔ Adds room availability updates.

✔ Uploads daily menu and charges.

✔ Tracks inquiries and payments from students.

---

## 👨‍💻 Author

---
### Adarsh Lilhare 

🎓 B.Tech in Artificial Intelligence & Data Science

💼 AI & Data Science Student | 💻 Developer | 🌍 Open Source Contributor

📧 [Email](adarshlilhare@example.com)

🐙 [GitHub](https://github.com/AdarshVL) 

🌐 [Portfolio](https://adarshlilhare.dev)

🔗 [LinkedIn](https://www.linkedin.com/in/adarsh-lilhare-b98a91290/)

---

🔹Expandable — anyone can contribute new modules

🔹Built for terminal-first learners and open-source enthusiasts

----
