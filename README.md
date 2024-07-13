# EasyBuy - E-commerce Platform

## Overview
EasyBuy is an e-commerce platform developed using React.js for the frontend and Spring Boot for the backend. The platform includes modules for both admin and customer, offering a comprehensive solution for online shopping and management.

## Modules

### Admin Key Features 🛒
- **🌟 Add New Products**: Add new products to our online store, complete with detailed information, images, and pricing.
- **📊 Efficient Order Management**: Dive into order management with features for updating order statuses and deleting orders, ensuring smooth operations for our business.
- **🗑️ Product Deletion**: Managing product catalog with the ability to delete products as necessary.

### Customer Key Features
- **Product Detail Page**: product detail page that will showcase our products in an engaging and informative manner. Users will be able to explore product images, descriptions, specifications, and more, providing them with all the necessary information to make informed purchasing decisions.
- **Shopping Cart**: features such as adding items, adjusting quantities, and removing products, ensuring that users can effortlessly manage their chosen items as they continue their shopping journey.
- **Delivery Address Form**: Develop a delivery address form that allows customers to enter their shipping details accurately, ensuring a smooth and hassle-free delivery process.
- **Order Summary Page**: Order summary page that provides users with a comprehensive overview of their selected items, quantities, and total costs. This page acts as a final checkpoint before customers proceed to the checkout process, ensuring complete transparency and clarity.
- **Order History Page**:  Order History page that allows your customers to conveniently track their previous purchases. Fetch and display order information, incorporate sorting and filtering options, and create a seamless user experience.
- **Order Details Page**: Order Details page that showcases specific details of selected orders. 

## Technologies Used
- **Frontend**: React.js
- **Backend**: Spring Boot
- **Database**: MySQL (or your preferred database)
- **Payment Gateway**: Stripe
- **Security**: JWT for authentication and authorization

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/DB4558/easybuy.git
   cd easybuy
### Backend Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/DB4558/springboot-backend-api.git
   cd springboot-backend-api
2. **Configure the database in src/main/resources/application.properties:**

   ```bash

      spring.datasource.url=jdbc:mysql://localhost:3306/springboot-backend-api
      spring.datasource.username=root
      spring.datasource.password=yourpassword

3. **Build and run the backend:**

      ```bash

          mvn clean install
          mvn spring-boot:run

4.**Frontend Setup**

    Clone the repository:

    ```bash

      git clone https://github.com/DB4558/react.git
      cd react
