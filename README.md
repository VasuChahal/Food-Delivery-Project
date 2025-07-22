# Food-Delivery-Project
##  📌 Intoduction 

This is a frontend Web Application built using React.js. The application simulates key features of real-world food delivery platforms like Swiggy and Zomato, providing users with a smooth and interactive experience. It allows users to browse food items, filter them by category, manage a shopping cart, and simulate order placement — all within a responsive and visually appealing interface.
## ✨ Features

- 🔐 **User Login Popup** – Allows users to log in with minimal distraction.
- 🍽️ **Menu Filtering** – Dynamically filter food items by category (e.g., Pizza, Burger, etc.).
- 🛒 **Cart Functionality** – Add/remove items, update quantity, and calculate total bill.
- 📦 **Order Placement** – Order summary and confirmation flow.
- 💡 **Context API Integration** – Global state management without prop drilling.
- 🔁 **React Router** – Dynamic routing for different pages.
- 📱 **Responsive UI** – Optimized for both desktop and mobile devices.

- ## 🧪 Technology Used & Purpose

| Technology        | Purpose                                                                 |
|-------------------|-------------------------------------------------------------------------|
| **React.js**      | Frontend framework to build a dynamic UI                                |                        |
| **React Router**  | To navigate between different pages without reloading the site          |
| **Context API**   | Manage global states like cart, login status, and menu filters          |
| **CSS**           | Custom styling for all components and responsiveness                    |

- ## ⚙️ How Functionality Works

🔐 Login System
- The login popup appears when the user initiates an action (e.g., adding to cart).
- User credentials are verified (can be mocked or connected to real backend).
- Once logged in, session state is saved using Context API.
- Based on login status, different UI elements (like Logout button or Welcome text) are conditionally rendered.

🍔 Menu Filtering
- All food items are displayed as cards with name, image, and price.
- Filter buttons (e.g., "Pizza", "Burger", "Drinks") allow category-based filtering.
- On clicking a filter, the list updates in real-time using React’s state management.

🛒 Cart & Order Flow
- When "Add to Cart" is clicked, the item is stored in global Context cart state.
- Quantity can be increased or decreased from the cart screen.
- Cart total is updated automatically as items are added or removed.
- Clicking “Place Order” shows a mock confirmation page and clears the cart.

📦 Dynamic Cart Total Calculation
- Cart items are looped over using JavaScript's reduce() method to calculate total.
- Any update in quantity or removal instantly reflects in the total amount.
- This gives a real-time billing experience similar to real food apps.

🚀 Page Routing & Navigation
- The app uses React Router for seamless navigation between pages (Home, Cart, Order Success).
- URL updates without full page reload, creating a Single Page Application (SPA) feel.
- Navigation bar helps users move between different sections smoothly.

