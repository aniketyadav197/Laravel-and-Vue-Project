# Customer Management System (Laravel & Vue.js)

This is a full-stack web application built with Laravel (backend) and Vue.js (frontend) to manage customers and their contacts efficiently.

## Features

### Module 1: Login & Registration
- Login page with email, password, and optional "Remember Me"
- Registration page with frontend validation (email format, password confirmation)
- Integration with backend authentication APIs using Axios
- Route guards for auth-protected pages with Vue Router
- Display of error and success messages for user feedback

### Module 2: Customer Management
- Paginated customer list displaying name, company, email, phone, and action buttons (view/edit/delete)
- Reusable form component for creating and editing customers
- Dynamic contact person section allowing multiple contacts with fields: name, designation, email, phone
- Ability to mark primary contact and remove contacts inline
- Frontend validation for customer and contacts data
- Customer detail page showing complete information and highlighting the primary contact
- State management using Vuex/Pinia for consistent data flow
- Reusable UI components like modals, inputs, and tables

## Technologies Used
- Backend: Laravel
- Frontend: Vue.js, Vue Router, Vuex/Pinia, Axios
- Database: MySQL/PostgreSQL
- Others: Bootstrap/CSS for styling

## How to Run
1. Clone the repository  
2. Install dependencies (`composer install` and `npm install`)  
3. Setup your `.env` for Laravel  
4. Run migrations (`php artisan migrate`)  
5. Serve Laravel backend (`php artisan serve`)  
6. Serve Vue frontend (`npm run serve` or equivalent)

## License
MIT License
