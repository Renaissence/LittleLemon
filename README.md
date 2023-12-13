Welcome to my Kickass API Repository!

Get ready to unleash the power of LittleLemon API and build awesome things!

This repository is your one-stop shop for all things related to my API. Think of it as your personal cheat sheet, playground, and documentation hub rolled into one.

What you'll find inside:

⚡️ Code: Dive into the source code and marvel at its clean structure and clever algorithms. Feel free to fork, tinker, and build upon my work. Just remember to give credit where credit is due!
** Documentation:** I've poured my heart and soul into crafting comprehensive documentation for every endpoint, parameter, and response. No more head-scratching, just smooth sailing.
⚙️ Examples: Need some inspiration? Check out the code examples for various use cases. They'll get you up and running in no time.
** Issues & Pull Requests:** Got a question, found a bug, or have a brilliant idea? Don't be shy! Open an issue or pull request and let's collaborate.
** Releases & Roadmap:** Stay in the loop with the latest releases and upcoming features. I'm always cooking up something new to make your API experience even better.
Why use my API?

** Blazing Fast:** My API is built for speed. Say goodbye to lag and hello to lightning-quick responses.
** Powerful Features:** I've packed this API with features that will make your life easier and your projects shine.
** Easy to Use:** I'm all about developer experience. You'll be up and running in no time, even if you're a complete API novice.
** Open & Collaborative:** I believe in the power of collaboration. My API is open-source, so you can contribute and make it even better.
Ready to get started?

Clone the repository:
gh repo clone Renaissence/LittleLemon

# Django-LittleLemon-API
This is a fully functioning API project for the Little Lemon restaurant so that the client application developers can use the APIs to develop web and mobile applications. People with different roles will be able to browse, add and edit menu items, place orders, browse orders, assign delivery crew to orders and finally deliver the orders.

Abilities:


1. The admin can assign users to the manager group
2. You can access the manager group with an admin token
3. The admin can add menu items 
4. The admin can add categories
5. Managers can log in 
6. Managers can update the item of the day
7. Managers can assign users to the delivery crew
8. Managers can assign orders to the delivery crew
9. The delivery crew can access orders assigned to them
10. The delivery crew can update an order as delivered
11. Customers can register
12. Customers can log in using their username and password and get access tokens
13. Customers can browse all categories 
14. Customers can browse all the menu items at once
15. Customers can browse menu items by category
16. Customers can paginate menu items
17. Customers can sort menu items by price
18. Customers can add menu items to the cart
19. Customers can access previously added items in the cart
20. Customers can place orders
21. Customers can browse their own orders


API Endpoints:

---User Registration and Token Generation Endpoints:

•	/api/users
•	/api/users/users/me/
•	/token/login/

---Menu Item Endpoints:

•	/api/menu-items
•	/api/menu-items
•	/api/menu-items/{menuItem}
•	/api/menu-items/{menuItem}
•	/api/menu-items
•	/api/menu-items
•	/api/menu-items/{menuItem}
•	/api/menu-items/{menuItem}
•	/api/menu-items/{menuItem}

---User group management endpoints:

•	/api/groups/manager/users
•	/api/groups/manager/users
•	/api/groups/manager/users/{userId}
•	/api/groups/delivery-crew/users
•	/api/groups/delivery-crew/users
•	/api/groups/delivery-crew/users/{userId}

---Cart management endpoints:

•	/api/cart/menu-items
•	/api/cart/menu-items
•	/api/cart/menu-items

---Order management endpoints:

•	/api/orders
•	/api/orders
•	/api/orders/{orderId}
•	/api/orders
•	/api/orders/{orderId}
•	/api/orders/{orderId}
•	/api/orders
•	/api/orders/{orderId}

