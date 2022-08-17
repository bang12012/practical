# What is Autorizz?
Autorizz is a web-based application developed to provide digital retail services to automotive dealerships in order to facilitate zero-contact sales and services. It manages and track the entire vehicle sales, service, parts inventory seamlessly connecting the dealership increasing its efficiency. The customers can browse and then view the complete specification of each vehicle listing with its features and buy the vehicle as per their requirements creating an awesome retail experience to the customer. This is a simple yet efficient management system to manage records of dealership data instead of using traditional methods to manage data like manual records or file systems. Their customers can always be in the comfort of their homes to check the various vehicles, spare parts listed in the website for sale as to their choice. Hence reducing the cost, saving time and increasing the comfort of their customers.

# Web Application
## 🙍‍♂️ Client End
### Home
<img width="600px" src="docs/assets/client_home.gif" alt="Home" />

### Electric Models
<img width="600px" src="docs/assets/electric_filters.gif" alt="Electric Index" />
 
#### Electric Models Booking
<img width="600px" src="docs/assets/electric_booking.png" alt="Electric Index" />
 
### Gas Models
<img width="600px" src="docs/assets/gas_filtering.gif" alt="Gas Index" />

#### Gas Models Booking
<img width="600px" src="docs/assets/gas_booking.png" alt="Gas Index" />

## 🛡️ Admin End
### Login
<img width="600px" src="docs/assets/admin_login.png" alt="Home" />

### Home
<img width="600px" src="docs/assets/admin_home_.png" alt="Home" />

### Manage Service
<img width="600px" src="docs/assets/admin_service.png" alt="Home" />

### Manage Models
<img width="600px" src="docs/assets/admin_models.png" alt="Home" />
 
### Manage Customers
<img width="600px" src="docs/assets/admin_cust.png" alt="Home" />


## 📋 Instructions
#### Application Structure
```
│
├── bin
├── models (MongoDB Mongoose Models)
├── node_modules 
├── public (application resources - css, js, images)
├── routes (handles admin, electric and gas routes)
├── views  (express-handlebars templates)
    ├── admin (admin templates)
    ├── layouts (default layout templates)
    └── electric and gas template files
├── app.js (root Node app script)
├── package.json
└── README.md
```
