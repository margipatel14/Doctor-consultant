# Adviisure - Online Doctor Appointment Booking System

**Adviisure** is an advanced online doctor appointment booking platform designed to connect patients with specialized doctors across various medical fields, including Gynecology, Dermatology, Neurology, General Medicine, Orthopedics, and more.  
The platform offers a seamless, intuitive interface that allows users to register, browse available doctors by specialty, check their availability, and book appointments in real time. Adviisure aims to minimize wait times, improve healthcare access, and streamline the consultation process — all while ensuring strong data security and user privacy.

---

## 🚀 Features

- User registration and authentication system  
- Browse and search doctors by specialty  
- Real-time appointment booking with calendar integration  
- Doctor profile pages with available time slots  
- Admin panel for managing doctors and appointments  
- Appointment confirmation and management  
- Mobile-friendly responsive design  
- Email notification support for users and doctors  
- Doctor login for schedule and availability management  

---

## ⚙️ Advanced Features

- **Role-based Authentication** for Admin, Doctor, and User access  
- **Real-time Availability Updates** for doctor's appointment slots  
- **Cloudinary Integration** for doctor profile images  
- **MongoDB Aggregation Pipelines** to manage and filter booking data  
- **RESTful API Design** for scalable backend logic  
- **Custom Middleware** for token verification and access protection  
- **Admin Dashboard** for complete system monitoring  

---

## 🔐 Security & Performance

- **Environment Variable Configuration** with `.env` files for API keys and secrets  
- **JWT Token Authentication** for secure session management  
- **CORS Policy Setup** for cross-domain access control  
- **Rate Limiting & Input Validation** to mitigate security risks  
- **Efficient MongoDB Queries** for optimal performance  
- **TailwindCSS** for fast, lightweight UI rendering  
- **Code Splitting in React** to enhance frontend performance  

---

## ✅ Test Cases

Here are some example test cases that validate core features:

- ✅ User can register, log in, and log out  
- ✅ User can view and filter list of doctors by specialty  
- ✅ User can successfully book an appointment  
- ✅ Doctor can log in and update availability  
- ✅ Admin can add or remove doctors  
- ✅ Unauthorized users cannot access protected routes  
- ✅ Booking system prevents double-booking for same time slot  
- ✅ Forms enforce proper validation for user inputs  

---

## 🧩 Tech Stack

- **Frontend**: ReactJS, TailwindCSS  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **Cloud Storage**: Cloudinary (for images)  
- **Authentication**: JWT-based  
- **Hosting**: Vercel / Render / MongoDB Atlas (cloud-hosted DB)

---

## 🛠️ Installation & Setup

To run this project locally, follow the steps below:

---

### 1. Clone the Repository

```bash
git clone https://github.com/margipatel14/Doctor-consultant.git
cd Doctor-consultant
```

---

### 2. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file in the `backend` directory with the following content:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

Start the backend server:

```bash
npm run dev
```

---

### 3. Setup Frontend

```bash
cd ../frontend
npm install
```
Create a `.env` file in the `frontend` directory with the following content:

```env
VITE_BACKEND_URL="http://localhost:4000"
```
Start the frontend server:

```bash
npm start
```

### 3. Setup Admin

```bash
cd ../admin
npm install
```
Create a `.env` file in the `admin` directory with the following content:

```env
VITE_CURRENCY="₹"
VITE_BACKEND_URL="http://localhost:4000"
ADMIN_EMAIL="Admin Email ID"
ADMIN_PASSWORD="Password"
```
Start the admin server:

```bash
npm start
```


## 📬 Contact

For issues, contributions, or feature requests, feel free to open an issue or a pull request.





