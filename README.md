# Dine Ease
A full-stack food ordering platform where users can browse, order, and manage food items. The platform includes user authentication, an intuitive dashboard, a seamless ordering experience, and is deployed on free-tier hosting services.

## Features

### Frontend
#### User Authentication
- Users can register and log in.
- Admin authentication with restricted access to manage food items and orders.

#### Food Dashboard
- Display a list of available food items with search and filter options.
- Categorized food items for easy navigation.

#### Order Management
- Users can add items to the cart and place orders.
- Real-time order status updates.

#### Responsive Design
- Optimized for desktops, tablets, and mobile devices.

### Backend
#### Authentication API
- Secure authentication using JWT for user login and registration.

#### Food Management API
- CRUD operations for food items and order management.
- Role-based access control for admin privileges.

#### Real-Time Updates
- WebSockets for real-time order status updates and interactions.

### Database
- User, food, and order data is stored efficiently in MongoDB or Planetscale.

## Deployment

### Frontend Hosting
- Deployed on **Vercel** or **Netlify** for free-tier hosting.

### Backend Hosting
- Deployed on **Render** or **Railway.app** for free-tier hosting.

### Database
- **MongoDB Atlas** (Free Plan) or **Planetscale** (Free Plan) is used for database hosting.

## Setup Instructions

### Prerequisites
- Node.js installed on your machine.
- MongoDB Atlas or Planetscale account for the database.

### Steps to Run Locally
1. Clone the repository:
   ```sh
   git clone https://github.com/Abhishek-Dhamshetty/dine-ease.git
   cd dine-ease
   ```
2. Install dependencies for both frontend and backend:
   ```sh
   npm install
   ```
3. Set up environment variables:
   - Create a `.env` file and configure database and authentication settings.

4. Start the development server:
   ```sh
   npm start
   ```

5. Open your browser and visit `https://dine-ease-puce.vercel.app/` to access the application.

