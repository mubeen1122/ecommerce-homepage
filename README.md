# E-Commerce Platform

A modern, full-featured e-commerce platform built with React, Vite, Tailwind CSS, and Zustand.

## Features

### Customer Features
- 🏠 Modern homepage with hero section, featured products, and testimonials
- 🛍️ Product browsing with advanced filtering and search
- 🛒 Shopping cart with real-time updates
- ❤️ Wishlist functionality
- 💳 Secure checkout process
- 👤 User authentication (Login/Register)
- 📊 Customer dashboard with order history
- 📱 Fully responsive design

### Admin Features
- 📈 Analytics dashboard with comprehensive metrics
- 📦 Product management (CRUD operations)
- 🏷️ Category and brand management
- 👥 Customer management
- 📋 Order management with status updates
- ⚙️ Settings panel (General, Store, Email, Payment, Security, SEO, etc.)
- 🔐 Secure admin authentication

## Tech Stack

- **Frontend Framework**: React 18
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **State Management**: Zustand with persistence
- **Routing**: React Router v6
- **Animations**: Framer Motion
- **Charts**: Recharts
- **Icons**: React Icons
- **HTTP Client**: Axios (ready for backend integration)

## Project Structure

```
src/
├── components/          # Reusable components
│   ├── admin/          # Admin panel components
│   ├── cart/           # Cart components
│   ├── checkout/       # Checkout components
│   ├── dashboard/      # User dashboard components
│   ├── home/           # Homepage components
│   ├── search/         # Search components
│   ├── shop/           # Shop page components
│   ├── static/         # Static page components
│   └── wishlist/       # Wishlist components
├── data/               # Mock data for development
├── pages/              # Page components
│   ├── admin/          # Admin pages
│   ├── auth/           # Authentication pages
│   └── dashboard/      # User dashboard pages
├── store/              # Zustand stores
├── App.jsx             # Main app component
└── main.jsx            # Entry point
```

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd <project-folder>
```

2. Install dependencies
```bash
npm install
```

3. Create environment file
```bash
cp .env.example .env
```

4. Start development server
```bash
npm run dev
```

5. Open your browser and navigate to `http://localhost:5173`

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Admin Access

To access the admin panel:
1. Navigate to `/admin/login`
2. Use demo credentials:
   - Email: admin@example.com
   - Password: admin123

## Features Overview

### Customer Side
- **Homepage**: Hero section, featured products, categories, testimonials
- **Shop**: Product listing with filters (category, brand, price, rating)
- **Product Details**: Image gallery, specifications, reviews, related products
- **Cart**: Add/remove items, quantity adjustment, coupon codes
- **Checkout**: Shipping information, payment method selection
- **Wishlist**: Save favorite products
- **User Dashboard**: Profile, orders, wishlist, payment methods
- **Search**: Global search with filters

### Admin Side
- **Dashboard**: Key metrics, recent orders, sales charts
- **Products**: Add, edit, delete products with image upload
- **Categories**: Manage product categories
- **Brands**: Manage product brands
- **Orders**: View and update order status
- **Customers**: View customer details and statistics
- **Analytics**: Comprehensive business insights with charts
- **Settings**: Configure store settings, email, payments, security, SEO

## State Management

The application uses Zustand for state management with the following stores:

- `useAuthStore` - Authentication state
- `useCartStore` - Shopping cart state
- `useWishlistStore` - Wishlist state
- `useShopStore` - Shop filters and products
- `useSearchStore` - Search functionality
- `useCheckoutStore` - Checkout process
- `useAdminStore` - Admin authentication
- `useProductManagementStore` - Product management
- `useCategoryStore` - Category management
- `useBrandStore` - Brand management
- `useOrderStore` - Order management
- `useCustomerStore` - Customer management
- `useAnalyticsStore` - Analytics data
- `useSettingsStore` - Application settings

## Styling

The project uses Tailwind CSS with custom configuration:
- Custom color palette (primary, secondary, accent)
- Responsive breakpoints
- Custom animations
- Gradient utilities

## Future Enhancements

- Backend API integration
- Real payment gateway integration
- Email notifications
- Product reviews and ratings
- Advanced search with Elasticsearch
- Multi-language support
- PWA capabilities
- Real-time order tracking

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Support

For support, email support@example.com or open an issue in the repository.
