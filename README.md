# **Django-React E-commerce Platform**

An integrated E-commerce application combining Django for the backend and React for the frontend, providing a seamless shopping experience.

---

## **Table of Contents**

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Backend Setup](#backend-setup)
  - [Frontend Setup](#frontend-setup)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)
---

## **Features**

- User authentication and profile management
- Product browsing and detailed views
- Shopping cart functionality
- Secure checkout process with payment integration
- Order history and tracking
- Responsive design for various devices

## **Technologies Used**

- **Backend:** Django
- **Frontend:** React

## In Updated Versions
(coming soon)
- **Backend:** Django, Django REST Framework
- **Frontend:** React, Redux
- **Database:** PostgreSQL
- **Payment Gateway:** Stripe
- **Styling:** Tailwind CSS
- **Deployment:** Docker, Nginx

## **Getting Started**

### **Backend Setup**

1. **Clone the Repository:**


2. **Create and Activate Virtual Environment:**

   - For macOS/Linux:

     ```bash
     python3 -m venv env
     source env/bin/activate
     ```

   - For Windows:

     ```bash
     python -m venv env
     .\env\Scripts\activate
     ```

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply Migrations and Create Superuser:**

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   python manage.py createsuperuser
   ```

5. **Start Development Server:**

   ```bash
   python manage.py runserver
   ```

### **Frontend Setup**

1. **Navigate to Frontend Directory:**

   ```bash
   cd frontend
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   ```

3. **Start Development Server:**

   ```bash
   npm start
   ```

## **Deployment**

1. **Build Frontend:**

   ```bash
   npm run build
   ```

2. **Environment Variables:**

   Set necessary environment variables for production in a `.env` file.

## **Contributing**

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## **License**

This project is licensed under the MIT License.

## **Acknowledgements**

Special thanks to the open-source community and the following resources:

- [Django Documentation](https://docs.djangoproject.com/)
- [React Documentation](https://reactjs.org/docs/getting-started.html)

---
