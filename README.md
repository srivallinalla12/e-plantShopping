# 🌿 e-Plant Shopping Website

A beginner-friendly e-commerce web app for plant shopping built with React. This project is part of the IBM Full Stack Developer Skills Network training program.


## 💡 Demo

https://srivallinalla12.github.io/e-plantShopping/


## 🛠️ Key Features & Learning Highlights
### 🌱  Plant Display:
The app dynamically displays a list of plants using plantsArray in ProductList.jsx, rendering details like name, category, image, description, and cost inside a div with the class product-grid.

### 🛒 Add to Cart Functionality:
Clicking "Add to Cart" triggers the handleAddToCart() function, which dispatches the selected plant to the Redux addItem() reducer in CartSlice.jsx.

### 🔁 State Management with Redux:
The CartSlice.jsx file handles adding, removing, and updating plant quantities using reducer functions (addItem, etc.). These reducers manage the cart's state centrally.

### 🧩 CartItems Component:
This component displays cart contents, enables quantity updates, subtotal and total calculations, item deletion, and supports "Continue Shopping" flow.

## 📖 How to Run Locally

### 1️⃣ Clone the repository:

```bash
git clone https://github.com/srivallinalla12/e-plantShopping.git
```
### 2️⃣ Navigate into the project directory:

```bash
cd e-plantShopping
```

### 3️⃣ Install dependencies:

```bash
npm install
```

### 4️⃣ Start the development server:
```bash
npm run dev -- --open
```

### 🌐 Deployment:
The app is deployed via GitHub Pages


## 🎯 Learning Objectives
- Build reusable React components with props and composition.
- Use React Hooks like useState and useEffect for state and lifecycle handling.
- Apply Redux for global state management (actions, reducers, store).
- Dynamically render UI from arrays using map().
- Handle user events and apply conditional rendering logic.




## ✅ License

This project is based on https://github.com/ibm-developer-skills-network/e-plantShopping, which is licensed under the Apache License 2.0.  
  
Modifications have been made by Srivalli Nalla.

See the [LICENSE](LICENSE) file for more details.
