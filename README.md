**MealMate**
--MealMate is a simple and efficient food delivery platform with two panels:
Admin: Manage food items and view customers.
Customer: Register, login, browse menu, add items to cart, and place orders.
Built with Python, Django, HTML, CSS, and SQLite.

**Key Features**
Admin: Add/edit/delete food items, view customers.
Customer: Register/login, browse menu, manage cart, place orders.

**Upcoming Enhancements**
1.Real-time order tracking
2.Delivery partner panel
3.Payment integration

**Challenges & Solutions**

Securing user access: solved using Django’s authentication system.

Managing roles: Admin vs Customer access handled with decorators.

**Technical Highlights**

Database: SQLite with Django ORM for smooth CRUD operations
Cart system: Linked to each user, dynamically updates totals
Forms: Validated using Django Forms
Templates & UI: HTML/CSS with template inheritance
Static & media files: Properly configured in Django settings
Orders: Tracked via Order model linked to User and Cart
Search & filter: Implemented with Django querysets and Q objects


**What I Learned**
Full-stack development with Django
Handling authentication, database, and user roles
Connecting frontend and backend efficiently
Building a functional web application from scratch
