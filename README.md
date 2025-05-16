# Glassify 🕶️

Glassify is an e-commerce website for purchasing lenses and glasses online. It offers a smooth browsing experience with user authentication, multiple pages, and a unique webcam-based **Virtual Try-On (VTO)** feature for trying glasses in 3D.

---

## Features

- 👓 **Virtual Try-On (VTO):**  
  Try different glasses on your face using your webcam, powered by the **Jeeliz VTO Widget**.

- 🔐 **Authentication:**  
  Secure Login and Registration pages.

- 🏠 **Multiple Pages:**  
  - Home  
  - Products  
  - About  
  - Blogs  
  - Contact

- 🛒 **E-commerce Capabilities:**  
  View/manage a cart, explore product SKUs, and enjoy a responsive UI.

- 📊 **CSV Product Management:**  
  Products managed via `glassesSKU.csv` for easy SKU handling.

---

## Technologies Used

- **HTML5 & CSS3**  
- **JavaScript**  
- **Jeeliz VTO Widget** (for 3D Try-On)  
- **ReactJS** 
- **Vite** (used with React demo)  
- **Font Awesome** (icons)  
- **CSV Parsing** (client-side product data)  
- **Webcam Access API**

---

## How to Run the Project

### Running the Static Website

1. Open any `.html` file (e.g., `home.html`, `products.html`) directly in your browser.  
2. On the **Home** page, click the **Suggest Now** button to be redirected to the **Try-On** page with the Virtual Try-On (VTO) feature—no separate launch needed.  
3. Make sure your browser has webcam permissions enabled for the Virtual Try-On functionality.

### Running the React Integration Demo

The React integration demo is available in the `reactIntegrationDemo` folder.

To run it:

```bash
cd reactIntegrationDemo
npm install
npm run start
```
Your default browser should open automatically at http://localhost:3000 (or the port specified).


Important: Use Node.js version 12 for compatibility:
  ```nvm use 12```

  ## 🔧 Note
  This project blends traditional frontend with modern React frameworks, showcasing a hybrid e-commerce experience with real-time 3D rendering.
