
# E-commerce Website

## Objective
Develop a high-performance and flexible e-commerce website using the MERN stack (MongoDB, Express.js, React, and Node.js). This application demonstrates the ability to manage products and users while ensuring a secure and user-friendly shopping experience across various devices.

## Features

### Product Management
- **Add, Update, and Delete Products:** Admins can manage the product catalog effectively.
- **Product Search and Filtering:** Users can search for products and apply various filters.

### User Management
- **Secure User Registration and Login:** Ensures that user data is protected with secure authentication mechanisms.
- **User Profile Management:** Users can update their profile information and view order history.

### Shopping Cart System
- **Add, Remove, and Modify Items:** Users can easily manage items in their shopping cart.
- **Persistent Cart:** Items in the cart are saved for future visits, even if the user logs out.

### Responsive Design
- **User-Friendly Interface:** Delivers a seamless shopping experience across various devices, including desktops, tablets, and smartphones.

### Order Management System
- **Order Tracking:** Users can track their orders, check shipping status, and receive delivery updates.
- **Admin Order Management:** Admins can view, update, and manage all orders.


## Technical Requirements

### Front-End
- **Framework/Library:** React.js
- **State Management:** Redux for managing the application state
- **Styling:** CSS, Material-UI (MUI) for responsive design

### Back-End
- **Server:** Node.js with Express.js framework
- **Database:** MongoDB for storing product, user, and order data
- **Authentication:** JWT (JSON Web Tokens) for secure user authentication


## Getting Started

### Prerequisites
- Node.js and npm installed on your machine
- MongoDB installed and running

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/ecommerce-website-mern.git
    ```

2. Navigate to the project directory:
    ```sh
    cd ecommerce-website-mern
    ```

3. Install server dependencies:
    ```sh
    cd backend
    npm install
    ```

4. Install client dependencies:
    ```sh
    cd ../frontend
    npm install
    ```

### Configuration
1. Create a `.env` file in the `backend` directory and add the following:
    ```env
   MONGO_URL=mongodb://localhost:27017/ecommercedata
   SECRET_KEY=your_secret_key_here
    ```

### Running the Application
1. Start the server:
    ```sh
    cd backend
    npm run dev
    ```

2. Start the client:
    ```sh
    cd frontend
    npm start
    ```

3. Open your browser and navigate to:
    ```sh
    http://localhost:3000
    ```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Inspiration from various e-commerce platforms.

![Ecommerce home](https://github.com/user-attachments/assets/20b25b6a-dbae-4d0d-b953-87e695875623)
![admin](https://github.com/user-attachments/assets/5c056812-decc-4a47-a581-b6c958405af0)
![addproduct](https://github.com/user-attachments/assets/fc8a129d-32b5-4fd1-bbe8-a45fc6d00cb6)
