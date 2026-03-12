# 💎 Shine

A sleek, high-performance e-commerce shopping cart application built with **React** and **Redux Toolkit**. Shine provides a seamless user experience for browsing products, managing a cart in real-time, and calculating costs dynamically.



## 🚀 Features

* **Real-time Cart Management**: Add or remove products with instant UI updates.
* **Smart Quantity Adjustments**: Increase or decrease item counts directly within the cart.
* **Dynamic Totals**: Automatic calculation of subtotal, taxes, and grand totals using Redux selectors.
* **Responsive Design**: Fully optimized for desktop, tablet, and mobile viewing.
* **State Persistence**: Built with Redux Toolkit for efficient, predictable state transitions.

## 🛠️ Tech Stack

* **Frontend**: React.js
* **State Management**: Redux Toolkit (RTK)
* **Styling**: CSS3 / Tailwind CSS (Update based on your specific styling)
* **Icons**: Lucide-React / FontAwesome

## 📦 Installation & Setup

Follow these steps to get the project running locally:

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/raymondoyondi/Shine.git](https://github.com/raymondoyondi/Shine.git)
    cd Shine
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Start the development server**
    ```bash
    npm start
    ```
    The app should now be running at `http://localhost:3000`.

## 🏗️ Project Structure

```text
src/
├── app/                # Redux store configuration
├── features/           # Redux slices (cartSlice, productSlice)
├── components/         # Reusable UI components (CartItem, Navbar, etc.)
└── App.js              # Main application entry
```

## 🧠 State Logic
The application leverages Redux Toolkit's `createSlice` to handle complex logic:

• `addItem:` Checks if the item exists; if so, increments quantity; if not, pushes new item.
• `removeItem:` Filters the state to remove specific product IDs.
• `calculateTotals:` A reducer that iterates through the cart to update the total price and badge count.

## 🤝 Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License
Distributed under the MIT License. See `LICENSE` for more information.
