<h3 align="center" style="text-align: center;">iOS developer Developer Interview Task</h3>

## Restaurant Business App

### Overview:

The app will simulate a restaurant's ordering system, allowing users to browse menu items, add them to the cart, and place orders. It will also keep track of the order history for each user.

### Requirements:

1. Create a new Xcode project with a Tabbed App template.

2. Implement the following tabs in the app:

   - Menu Tab:

     - Display a list of menu categories (e.g., Appetizers, Main Course, Desserts).
     - When the user selects a category, show a list of menu items within that category.
     - Each menu item should have a name, description, price, and an option to add it to the cart.

   - Cart Tab:

     - Show a list of items added to the cart by the user.
     - Display the item name, quantity, and total price for each item in the cart.
     - Allow the user to adjust the quantity of items or remove items from the cart.
     - Display the total order amount.
     - Include a "Place Order" button to proceed to the order confirmation.

   - Order History Tab:
     - Show a list of previous orders placed by the user.
     - Each order should display the order date, total amount, and order status (e.g., pending, completed, delivered).
     - Tapping on an order should show the order details with individual items and their quantities.

3. Implement Data Management:

   - Use Core Data or Realm to manage the app's local data, including the menu items, cart items, and order history.

4. Networking and API Integration:

   - Create a mock API to simulate data retrieval from a server.
   - Implement API calls to fetch the menu items and send order details to the server.
   - For the sake of this test project, the server can be simulated using JSON files or a simple backend (you can use JSONPlaceholder or similar).

5. UI/UX Design:

   - Design an attractive and user-friendly interface for the app, with appropriate use of colors, icons, and images.
   - Ensure the app is responsive and compatible with different device sizes and orientations.

6. Error Handling and Validation:

   - Implement proper error handling and validation for scenarios like failed API calls, empty cart, etc.
   - Display relevant error messages to the user when necessary.

7. Extra Credit (Optional):
   - Implement user authentication and user accounts to keep track of individual users' orders and order history.
   - Include support for real-time updates to order status (e.g., push notifications when an order status changes).

Remember, this is a challenging project, so take your time and focus on writing clean and well-organized code. Good luck!
