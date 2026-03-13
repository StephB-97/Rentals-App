# 🏠 Rentals

A full-stack web application for browsing and managing rental property listings. Built with Node.js, Express, MongoDB, and EJS templating.

---

## 📸 Features

- Browse rental property listings
- Create, edit, and delete listings
- Upload property images via Cloudinary
- User authentication and session management
- Form validation with custom error handling
- Responsive UI

---

## 🛠️ Tech Stack

| Layer       | Technology                        |
|-------------|-----------------------------------|
| Runtime     | Node.js                           |
| Framework   | Express.js                        |
| Database    | MongoDB + Mongoose                |
| Templating  | EJS                               |
| Image Upload| Cloudinary + Multer               |
| Auth        | express-session + connect-mongo   |
| Validation  | Joi                               |
| Styling     | CSS / Bootstrap                   |

---

## 📁 Project Structure

```
Rentals/
├── cloudinary/       # Cloudinary configuration
├── controllers/      # Route handler logic
├── models/           # Mongoose data models
├── public/           # Static assets (CSS, JS, images)
├── routes/           # Express route definitions
├── seeds/            # Database seed scripts
├── utils/            # Helper utilities & error handlers
├── views/            # EJS templates
├── app.js            # Main application entry point
├── middleware.js     # Custom middleware
├── schemas.js        # Joi validation schemas
└── package.json
```

---

## ⚙️ Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher)
- [MongoDB](https://www.mongodb.com/) (local or [Atlas](https://www.mongodb.com/atlas))
- [Cloudinary](https://cloudinary.com/) account

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/StephyB-97/Rentals.git
   cd Rentals
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env` file in the root directory:
   ```env
   MONGODB_URI=your_mongodb_connection_string
   CLOUDINARY_CLOUD_NAME=your_cloud_name
   CLOUDINARY_KEY=your_api_key
   CLOUDINARY_SECRET=your_api_secret
   SESSION_SECRET=your_session_secret
   ```

4. **(Optional) Seed the database**
   ```bash
   node seeds/index.js
   ```

5. **Start the app**
   ```bash
   npm start
   ```

6. Open your browser and go to `http://localhost:3000`

---

## 🚀 Deployment

This app can be deployed to any Node.js-compatible platform. Recommended options:

- **[Render](https://render.com)** — Connect your GitHub repo and add environment variables
- **[Railway](https://railway.app)** — Import from GitHub with MongoDB add-on support
- **[Fly.io](https://fly.io)** — CLI-based deployment with great scalability

> Make sure to use **MongoDB Atlas** for your cloud database and set all environment variables on your hosting platform.

---

## 🔐 Environment Variables

| Variable                | Description                        |
|-------------------------|------------------------------------|
| `MONGODB_URI`           | MongoDB connection string           |
| `CLOUDINARY_CLOUD_NAME` | Your Cloudinary cloud name          |
| `CLOUDINARY_KEY`        | Cloudinary API key                  |
| `CLOUDINARY_SECRET`     | Cloudinary API secret               |
| `SESSION_SECRET`        | Secret for signing session cookies  |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👩‍💻 Author

**StephyB-97** — [GitHub](https://github.com/StephyB-97)
