# Inventory-Management-System

A robust Inventory Management System built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. This application helps businesses manage their inventory effectively, track stock levels, and generate detailed reports.

## Features

### Admin Features:
- **Product Management:** Add, update, and delete products.
- **Category Management:** Organize products into categories.
- **Stock Management:** Track stock levels in real-time.
- **Order Management:** Process incoming orders and update inventory.
- **Reports:** Generate sales and stock reports.

### User Features:
- **Authentication:** Secure login and registration.
- **Product Catalog:** Browse and search available products.
- **Order Placement:** Add items to the cart and place orders.
- **Order History:** View past orders with status updates.

## Tech Stack

- **Frontend:** React.js, Redux (for state management), Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (NoSQL)
- **API Testing:** Postman

## Installation

### Prerequisites:
- Node.js (v16+)
- npm or Yarn
- MongoDB

### Steps to Run Locally:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/inventory-management-system.git
   cd inventory-management-system
   ```

2. **Set Up Backend:**
   ```bash
   cd backend
   npm install
   ```
   - Create a `.env` file and configure the following variables:
     ```env
     PORT=5000
     MONGO_URI=<your-mongodb-connection-string>
     JWT_SECRET=<your-secret-key>
     ```
   - Start the backend server:
     ```bash
     npm start
     ```

3. **Set Up Frontend:**
   ```bash
   cd ../frontend
   npm install
   ```
   - Start the frontend development server:
     ```bash
     npm start
     ```

4. **Access the Application:**
   - Frontend: `http://localhost:3000`
   - Backend: `http://localhost:5000`

## Folder Structure

```
inventory-management-system/
├── backend/           # Backend code
│   ├── config/        # Configuration files
│   ├── controllers/   # API logic
│   ├── models/        # MongoDB models
│   ├── routes/        # API routes
│   └── server.js      # Entry point for backend
├── frontend/          # Frontend code
│   ├── src/           # React application
│   │   ├── components/ # Reusable components
│   │   ├── pages/     # Page components
│   │   ├── redux/     # State management
│   │   └── App.js     # Main app component
├── README.md          # Project documentation
```

## API Endpoints

### Authentication:
- `POST /api/users/register`: Register a new user
- `POST /api/users/login`: Log in a user

### Products:
- `GET /api/products`: Get all products
- `POST /api/products`: Add a new product
- `PUT /api/products/:id`: Update product details
- `DELETE /api/products/:id`: Delete a product

### Orders:
- `GET /api/orders`: Get all orders
- `POST /api/orders`: Place an order
- `PUT /api/orders/:id`: Update order status

## Future Improvements

- Integration with payment gateways
- Role-based access control (admin, staff, customer)
- Push notifications for stock alerts
- Barcode scanner integration

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contributions

Contributions are welcome! Please fork the repository and submit a pull request.

## Contact

For queries or feedback, reach out to:
- **Name:** Virendra Singh Rawat
- **Email:** virendrasinghrawat2812@gmail.com
- **GitHub:** [vrndrrwt](https://github.com/vrndrrwt)

---

Manage your inventory efficiently with this modern Inventory Management System!
