# MenuPal
MenuPal is a restaurant management system that uses data structures to enable efficient menu viewing, order placement, and real-time tracking.

This project is a restaurant management system that allows customers to view the menu, place orders, and search for specific items. It also includes an admin panel for managing the menu, viewing bills, and tracking payments. The system uses various data structures to manage and process data efficiently.

---

## Features

### Customer Panel:
1. **Show Menu**: Displays the available food items along with their details (name, price, stock).
2. **Place Order**: Allows customers to select food items, specify quantities, and make payments (credit card or cash).
3. **Search Food by Name**: Enables customers to search for food items by their name.

### Admin Panel:
1. **Show Menu**: Displays the current menu.
2. **Add Food**: Adds new food items to the menu.
3. **Remove Food**: Removes food items from the menu.
4. **Show Bill for Table**: Displays the total bill for a specific table.
5. **Show Payments**: Displays payment details, including credit card numbers and amounts.

---

## Data Structures Used

### 1. **Linked List** (for managing the menu):
   - **Structure**: `Food`
     - Contains fields such as `foodNo`, `name`, `price`, `stock`, and a pointer to the next node.
   - **Usage**: Stores the menu items and allows dynamic addition/removal of items.

### 2. **Queue** (for managing customer orders):
   - **Structure**: `Queue`
     - Contains fields such as `tableNo`, `foodNo`, `quantity`, and a pointer to the next node.
   - **Usage**: Handles customer orders in a first-come-first-served manner.

### 3. **Stack** (for navigation in the user interface):
   - **Structure**: `Stack`
     - Contains a single integer field and a pointer to the next node.
   - **Usage**: Keeps track of navigation between customer and admin panels.

### 4. **Binary Search Tree (BST)** (for managing payments):
   - **Structure**: `PaymentNode`
     - Contains fields such as `creditCardNumber`, `amount`, and pointers to left and right child nodes.
   - **Usage**: Efficiently stores and retrieves payment details.
