# E-commerce Project: Glassify Store

Welcome to the **Glassify Store** project! This is a modern, responsive e-commerce website for selling eyewear, including sunglasses, prescription glasses, and fashion lenses.

## Features

### User Features
- **Homepage**: Showcases featured products and promotions.
- **Product Listing**: Displays all available products with filters and search functionality.
- **Product Details**: Detailed page for each product, including price, description, and reviews.
- **Shopping Cart**: Allows users to view and modify their selected items.
- **Checkout**: Secure checkout process for payments.
- **User Authentication**: Login and registration functionality.
- **Contact Page**: Provides a way to contact the store for inquiries.

### Admin Features (Future Implementation)
- Manage product inventory.
- View and process customer orders.
- Analyze sales data.

## Project Structure

```
.
├── pages
│   ├── index.js          # Homepage
│   ├── products
│   │   ├── index.js      # Product listing page
│   │   ├── [id].js       # Product details page
│   ├── cart.js           # Shopping cart page
│   ├── checkout.js       # Checkout page
│   ├── login.js          # Login page
│   ├── register.js       # Registration page
│   ├── about.js          # About us page
│   ├── contact.js        # Contact page
│   ├── api
│       ├── products.js   # API for products
│       ├── cart.js       # API for cart management
│       ├── checkout.js   # API for checkout
├── components
│   ├── Navbar.js         # Navigation bar
│   ├── Footer.js         # Footer
│   ├── ProductCard.js    # Product card component
│   ├── CartItem.js       # Cart item component
│   ├── Button.js         # Reusable button component
│   ├── Modal.js          # Modal component
├── styles
│   ├── globals.css       # Global styles
│   ├── navbar.css        # Navbar styles
│   ├── footer.css        # Footer styles
│   ├── productcard.css   # Product card styles
│   ├── cartitem.css      # Cart item styles
├── public
│   ├── images
│       ├── logo.png      # Logo image
│       ├── banner.jpg    # Homepage banner
└── README.md             # Project documentation
```

## Setup and Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-repo/glassify-store.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd glassify-store
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Run the development server**:
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) to view the site.

5. **Build for production**:
   ```bash
   npm run build
   ```

6. **Start the production server**:
   ```bash
   npm start
   ```

## Technologies Used
- **Next.js**: Framework for server-rendered React applications.
- **React.js**: Component-based library for building user interfaces.
- **CSS Modules**: Styling components with scoped CSS.
- **API Routes**: Backend API functionality built into Next.js.

## Future Enhancements
- Add admin dashboard for managing products and orders.
- Implement user reviews and ratings.
- Add payment gateway integration for secure payments.
- Include product recommendations based on user preferences.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

---

Happy coding!
