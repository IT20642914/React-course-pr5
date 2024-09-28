# React-course-pr5
# Elegant Context

**Elegant Context** is a simple eCommerce web application built using **React**. It showcases a modern shopping experience where users can browse through a list of products, add them to their shopping cart, and manage the quantity of items in the cart before proceeding to checkout. This project was developed as part of a React course requirement, focusing on advanced state management using **Context API** and the **useReducer** hook.
![image](https://github.com/user-attachments/assets/fb778515-f4f4-4edf-8d25-f39b2af08260)

![image](https://github.com/user-attachments/assets/d3687c08-e52c-48b3-9a26-ea4a3e5689ad)

## Features

- **Product Display**: Browse through a collection of products displayed dynamically from a dummy product list.
- **Add to Cart**: Users can add items to their cart with a single click.
- **Cart Management**: Update the quantity of items directly in the cart, including the ability to increase or decrease the item count.
- **Cart Modal**: A modal view that displays the current items in the cart, total price, and options to checkout or close the cart.
- **State Management**: The application uses **Context API** combined with **useReducer** to manage the state of the shopping cart across different components.

## Technology Stack

- **React**: A JavaScript library for building user interfaces.
- **Context API & useReducer**: Used for state management, handling the shopping cart and item quantities.
- **CSS**: Basic styles for layout and design.
- **JSX**: For defining component structure.

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/elegant-context.git

## Project Structure

- **components/**:  
  Contains reusable UI components like `Header`, `Shop`, and `Product`. These components are responsible for the overall layout and functionality of the front-end user interface.

- **store/**:  
  Manages the cart state using the `CartContext` and `shopping-cart-context.jsx`. This directory centralizes the application's state management for the shopping cart, making it accessible across different components.

- **dummy-products.js**:  
  A static data file that contains a list of dummy products used for testing and demonstration purposes.

- **App.js**:  
  The root component that wraps the entire application within the `CartContextProvider`, providing the global cart state to all components of the application.

---

## Key Features and Concepts

- **Context API & useReducer**:  
  The project leverages React's Context API to provide global state management. It uses the `useReducer` hook to handle complex state transitions and updates within the shopping cart. This setup ensures that all components have access to the cart state, while `useReducer` manages the logic for adding, removing, or updating items in the cart.

- **useRef for Modals**:  
  The shopping cart modal window uses React's `useRef` to handle its visibility and control, making it possible to open and close the modal programmatically.

- **Dynamic Product Rendering**:  
  Products in the application are rendered dynamically from a static array (`dummy-products.js`). This allows for scalability, as adding new products or modifying existing ones can be done simply by updating the array.

---
