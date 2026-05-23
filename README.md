# Zalengam Express - Ride-Hailing Platform

A modern, user-friendly ride-hailing application that connects customers with service providers in Kukiland.

## 🚀 Features

### For Customers
- 🚗 **Easy Ride Booking** - Simple booking process
- 📍 **Real-Time Location Tracking** - Track driver location in real-time
- 💳 **Multiple Payment Options** - UPI, GPay, FamPay, Cash, and Wallet
- ⭐ **Ratings & Reviews** - Rate drivers and share feedback
- 💰 **Dynamic Pricing** - Fair pricing based on distance and demand
- 🏠 **Saved Locations** - Save frequent locations for quick booking
- 💼 **Wallet Management** - Add and manage wallet balance

### For Drivers
- 📍 **Device Location Integration** - Automatic location updates
- 🎯 **Accept/Decline System** - Accept rides with instant customer notifications
- 📊 **Earnings Dashboard** - Track daily earnings
- 🏦 **Easy Withdrawal** - Multiple withdrawal options
- ⭐ **Driver Ratings** - Build reputation with customer reviews
- 📱 **Ride History** - Complete record of all rides

### For Admin
- 👨‍💼 **Driver Management** - Approve and manage driver profiles
- 💰 **Dynamic Pricing** - Set base fares, per-km rates, peak hour surcharges
- 📈 **Revenue Reports** - Detailed analytics on platform revenue
- 👥 **User Management** - Manage customers and drivers
- 🚗 **Fleet Tracking** - Real-time tracking of all active rides

## 🛠 Tech Stack

### Backend
- Node.js & Express.js
- MongoDB
- Socket.IO (Real-time tracking)
- JWT Authentication
- Bcryptjs

### Frontend
- React.js
- React Router
- Axios
- Tailwind CSS
- Socket.IO Client

## 📦 Installation

### Prerequisites
- Node.js (v14+)
- MongoDB
- Git

### Backend Setup

```bash
git clone https://github.com/singsitsehminlal/zalengam-express.git
cd zalengam-express
npm install
cp .env.example .env
npm run dev
```

### Frontend Setup

```bash
cd client
npm install
npm start
```

## 🌍 API Endpoints

### Auth
- `POST /api/auth/register` - Register user
- `POST /api/auth/login` - Login user
- `GET /api/auth/verify` - Verify token

### Rides
- `POST /api/rides/request` - Request ride
- `GET /api/rides/available` - Get available rides
- `POST /api/rides/:rideId/accept` - Accept ride
- `POST /api/rides/:rideId/decline` - Decline ride

### Payments
- `POST /api/payments/process` - Process payment
- `GET /api/payments/history` - Payment history

### Admin
- `GET /api/admin/dashboard/stats` - Dashboard stats
- `GET /api/admin/drivers` - All drivers
- `PUT /api/admin/pricing` - Update pricing

## 💳 Payment Methods
- UPI
- Google Pay
- FamPay
- Cash
- Digital Wallet

## 📝 License

MIT License

---

**Made with ❤️ for Kukiland riders and drivers**
