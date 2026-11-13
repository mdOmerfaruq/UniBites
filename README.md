# UniBites – University Food Ordering & Campus Delivery Platform

UniBites is a university-focused food ordering and campus delivery platform designed to connect students with campus canteen stalls and delivery partners. It provides an integrated interface for browsing food, managing carts, placing orders, tracking order status, and managing rider activities.

## Technologies Used

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Local Development Environment:** XAMPP
- **Cart Management:** JavaScript LocalStorage

## Main Features

### User Management
- User registration and login
- User profile management
- Account information and recent activity

### Food Ordering
- Browse food items
- Search and filter foods
- Explore canteen stalls
- Add items to cart
- Checkout and order placement
- Cash on Delivery and online payment options

### Order Management
- View order history
- Track order status
- Manage pending orders

### Rider Management
- Apply as a delivery partner
- View available delivery requests
- Accept delivery requests
- View completed deliveries and earnings

### Additional Features
- Responsive user interface
- Dark-themed design
- Customer support page
- Ratings and reviews
- Campus-focused delivery experience

## Project Structure

```text
UniBites/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── cart.js
└── pages/
    ├── signin.html
    ├── signup.html
    ├── foods.html
    ├── canteen.html
    ├── checkout.html
    ├── orders.html
    ├── history.html
    ├── profile.html
    ├── earn.html
    ├── earnings.html
    └── support.html
```

Additional PHP API, database, and backend directories can be added as implementation progresses.

## Database Design

The planned MySQL database includes:

- Users
- Stalls
- Foods
- Orders
- Order Items
- Deliveries
- Reviews

## Local Setup

1. Install XAMPP.
2. Start Apache and MySQL.
3. Place the project inside `C:\xampp\htdocs\`.
4. Create a MySQL database named `unibites`.
5. Import the project's SQL database file using phpMyAdmin.
6. Configure the PHP database connection.
7. Open the application:

```text
http://localhost/UniBites/
```

## Design System

| Element | Value |
|---|---|
| Primary Color | #FFA500 |
| Background | #0D0D0D |
| Card Background | #1A1A1A |
| Input Background | #2A2A2A |
| Border | #333333 |
| Font | Inter |

## Project Goal

To develop a convenient digital food ordering and campus delivery solution that improves the food ordering experience for university students and supports campus food vendors and delivery partners.

## Developer

**Md. Omer Faruq**

GitHub: [Your GitHub Profile](https://github.com/mdOmerfaruq)

---

*Note: Features and backend integrations should be considered implemented only where the corresponding functionality exists in the source code.*
