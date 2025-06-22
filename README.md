# Apparel Store Project

## Project Description
This is a modern, responsive e-commerce web application focused on apparel products. The app showcases a variety of clothing items and accessories with detailed product pages, shopping cart functionality, and a clean, user-friendly interface. It is designed to provide a seamless shopping experience with features like product browsing, detailed views, and easy checkout.

## Technologies and Frameworks Used
- **Next.js**: React framework for server-side rendering and static site generation.
- **React**: For building UI components.
- **Tailwind CSS**: Utility-first CSS framework for styling and responsive design.
- **Context API**: For managing the shopping cart state globally.
- **Pexels API (Images)**: Public image URLs from Pexels are used for product images.
- **JavaScript (ES6+)**: Modern JavaScript features for clean and efficient code.

## Project Structure
- `src/lib/products.js`: Contains the product data array.
- `src/app/page.jsx`: Home page displaying the product grid.
- `src/components/ProductCard.jsx`: Component to render individual product cards.
- `src/app/product/[id]/page.jsx`: Dynamic product detail page.
- `src/context/CartContext.jsx`: Context provider for cart state management.
- Other UI components like NavBar, Footer, and Checkout pages.

## How to Run the Project

### Prerequisites
- Node.js (version 14 or above)
- npm or yarn package manager

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd <project-directory>
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
   or
   ```bash
   yarn install
   ```

### Running the Development Server
Start the development server on port 8000:
```bash
PORT=8000 npm run dev
```
or
```bash
PORT=8000 yarn dev
```

Open your browser and go to `http://localhost:8000` to view the app.

### Building for Production
To build the project for production:
```bash
npm run build
```
or
```bash
yarn build
```

To start the production server:
```bash
npm start
```
or
```bash
yarn start
```

## Features
- Responsive product grid with modern UI.
- Detailed product pages with images, descriptions, and features.
- Add to cart and buy now functionality.
- Error handling for invalid product pages.
- Clean and maintainable codebase using React and Tailwind CSS.

## License
This project is open source and available under the MIT License.
