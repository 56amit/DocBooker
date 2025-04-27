                                                              DocBooker - Doctor Appointment Booking System
                                                              🔗 Live Demo: https://docbooker-frontend-tvuy.onrender.com
A full-stack web application to easily book doctor appointments, manage doctor profiles (with images), and handle user, doctor, and admin operations.

                                                             Features
User Registration and Login (JWT Authentication)

Role-based Access: User, Doctor, Admin

Search Doctors and Book Appointments

Doctor Profile Upload (with Cloudinary Image Storage)

Admin Approval/Rejection of Doctor Profiles

View Upcoming and Past Appointments

Notification System for Users and Doctors

Profile Management for Users and Doctors

Secure API Routes with Middleware (Auth Protection)

Fully Responsive Frontend with TailwindCSS

                                                       Technologies Used
                                                       Frontend:

React.js

Vite

TailwindCSS (for responsive UI)

Axios (for API communication)

React Router DOM (for routing)

Context API (global state management)

                                                        Backend:

Node.js

Express.js (server framework)

MongoDB (with Mongoose ODM)

Multer (to handle image uploads)

Cloudinary (to store uploaded images in cloud)

JSON Web Tokens (JWT) for Authentication

Bcrypt.js (for password encryption)

Hosting:

Backend: Render

Frontend: Render / Vercel / Netlify (mention based on your hosting)

                                                  📂 Project Structure
arduino
Copy
Edit
/frontend
    ├── src
    │   ├── components
    │   ├── pages
    │   ├── context
    │   ├── utils
    │   ├── assets
    │   └── App.jsx
    └── vite.config.js

/backend
    ├── models
    ├── controllers
    ├── routes
    ├── middlewares
    ├── utils (Cloudinary setup here)
    └── server.js
📷 How Image Upload Works
Users (Doctors) upload profile images.

Multer handles the upload in the backend.

Uploaded files are directly sent to Cloudinary cloud storage.

Cloudinary returns a secure URL, which is saved in MongoDB under the doctor's profile.

⚙️ How to Run Locally
Clone the project:

bash
Copy
Edit
git clone https://github.com/56amit/DocBooker.git
cd DocBooker
Install Frontend Dependencies:

bash
Copy
Edit
cd frontend
npm install
Install Backend Dependencies:

bash
Copy
Edit
cd ../backend
npm install
Create Environment Variables:

Create a .env file inside /backend:

env
Copy
Edit
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
And inside /frontend, create a .env:

env
Copy
Edit
VITE_BACKEND_URL=https://your-backend-url.onrender.com
Run the Project:

Open two terminals:

Backend:

bash
Copy
Edit
cd backend
npm start
Frontend:

bash
Copy
Edit
cd frontend
npm run dev
Visit: http://localhost:3000

📸 Screenshots (Optional)
(Add some nice UI screenshots of Login Page, Doctor List, Booking Page, Admin Dashboard, etc.)

🙏 Acknowledgements
MongoDB Atlas

Cloudinary

Render

TailwindCSS

Vite

📬 Contact
Name: Amit Kumar Pandey

Email: amit760729@gmail.com

LinkedIn: [https://www.linkedin.com/in/amit-pandey-04bba325b]

                                                                    ✨ Thank You for Visiting DocBooker! ✨



