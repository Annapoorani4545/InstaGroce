# InstaGroce
Online Grocery Store

Overview:
InstaGroce is a dynamic web application that seamlessly handles product management, user 
authentication, shopping carts, and various functionalities. It is a multi-user app(admin, store 
manager and other users) for buying products in one or multiple sections, with admin and store 
manager having access to add, edit or delete products and sections, the changes visible to users 
immediately on the application. This application has been meticulously crafted using the Flask web 
framework and leverages the power of Jinja2 templates to create dynamic HTML content. In the 
following sections, we'll delve into the intricacies of the underlying models and the holistic system 
design.


Models:
• User Model: The User model serves as a representation of registered users within the 
application. It encompasses essential fields such as username, email, password hash, and an 
'is_admin' indicator to ascertain admin privileges.
• Product Model: The Product model embodies individual items within the system. It captures 
attributes like name, manufacture date, expiry date, unit rate, category, and available stock 
units.
• Category Model: The Category model defines distinct product categories. It simplifies 
categorization with a single 'name' attribute.
• Cart Item Model: The Cart Item model is employed for the purpose of storing items added to 
the shopping cart. It establishes connections with both the User and Product models via 
foreign keys, representing the user who added the item and the specific product being 
included in the cart.
System Design:
The application adheres to a modular design approach, prioritizing the separation of concerns and 
ease of maintenance. Below is an overview of its key components:
▪ Templates: These templates are responsible for dynamically rendering HTML content. 
Crafted using Jinja2, they are categorized by distinct views, including user authentication, 
product management, shopping cart, and more.
▪ Routes: Routes define the URL endpoints that correspond to various functionalities. They 
manage user requests, interact with the models, and facilitate the rendering of the 
appropriate templates.
▪ User Authentication: The application offers user registration, login, and admin login features. 
User passwords undergo secure hashing before storage for enhanced security.
▪ Product Management: Administrators have the ability to oversee products and categories. 
They can perform actions such as adding, editing, and deleting products and categories.
▪ Shopping Cart: Users can seamlessly add products to their shopping cart, review its contents, 
and clear the cart if needed. The cart's functionality is closely tied to the Cart Item model.
▪ Search Functionality: The application boasts a robust search feature that empowers users to 
filter products based on criteria like category, max budget, and date range for a refined 
shopping experience.


Key Features:
✓ User Registration and Authentication: This feature enables users to securely create accounts 
and log in using passwords, ensuring personalized access to the application.
✓ Admin Login for Product and Category Management: Administrators have a dedicated login 
portal to efficiently manage products and categories, distinct from regular user access.
✓ Product and Category CRUD Operations: Admins have full control over product and category 
management, with the ability to create, read, update, and delete items as needed.
✓ Shopping Cart Functionality with User-Linked Cart Items: Authenticated users can easily add 
products to their shopping carts, with cart items being associated with their respective 
accounts for a seamless shopping experience.
✓ Search Functionality for Product Filtering: Users can take advantage of a robust search 
feature to filter products based on a range of attributes, including category, price range, and 
date.
✓ Template-Driven UI for Consistent Views: The application's user interface is structured 
around HTML templates, ensuring a cohesive and organized appearance throughout various 
sections of the app.
✓ Utilization of Flask Extensions for Form Handling and URL Routing: Flask extensions are 
employed to streamline form creation and validation, as well as manage URL routing, 
facilitating efficient and effective development.
Conclusion:
In summary, the InstaGroce App Grocery Store MAD 1 project exemplifies a meticulously designed 
and feature-enriched web application constructed on the Flask framework. With its modular 
architecture, robust user authentication, streamlined product and category management, smooth 
shopping cart experience, and powerful search functionality, the application delivers a user-friendly 
and well-organized platform for online shopping. Furthermore, the integration of Flask extensions 
enhances form handling and URL routing, further enhancing its robust and user-focused design.


Video Presentation Link:
https://drive.google.com/file/d/1LcEQ0m_DiI6AOD6ZeOIMcAFJQSDs0xuu/view?usp=
sharing
