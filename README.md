MealMate

MealMate is a food delivery system with two panels:

Admin panel: Manage food items and customers.

Customer panel: Register, login, browse food, add to cart, and place orders.

Built with Python, Django, HTML, CSS, and SQL.

Features

Admin:

Add, edit, delete food items

View customers

Customer:

Register and login

View menu

Add items to cart

Place orders

Upcoming Features

Real-time order tracking

Delivery partner panel

Payment integration

Challenges

Handling user authentication to restrict access: solved using Django’s built-in auth system.

Technical Details

Database: SQLite with Django ORM for easy CRUD operations

Cart system: Cart model linked to users, dynamically updates total before checkout

User roles: Added role field to distinguish Admin and Customer, access restricted with decorators

Forms: Validated using Django Forms

Templates & UI: HTML/CSS with Django template tags and inheritance

Static & media files: Configured STATIC and MEDIA directories

Security: Password hashing, input validation, login-required decorators

Orders: Order model linked to User and Cart

GET & POST: GET fetches data; POST sends data

Django MVT architecture: Model (DB), View (logic), Template (frontend)

Database migrations: makemigrations → migrate

Login/logout: Django auth functions

Error handling: Custom templates & try-except in views

Search/filter: Django querysets with filter() and Q objects

What I Learned

Full-stack development with Django

Database management & authentication

Connecting frontend & backend

Solving real web development problems
