#11253177

# App Name : Open Fashion App

## Design Choices

### UI/UX Design

1. **Minimalist Design**:

   - The app employs a clean, minimalist design to ensure the focus remains on the products.
   - White backgrounds and simple fonts contribute to an elegant look and feel.

2. **Easy Navigation**:

   - A hamburger menu located on the top left enables users to navigate through different sections of the app.
   - A search icon on the top right facilitates quick product searches.

3. **Product Display**:

   - Products are presented in a grid format on the main page, making it easy for users to browse through the available items.
   - Each product card includes an image, title, and price for easy identification.

4. **Checkout Page**:
   - The checkout page lists selected products with their images, titles, and prices.
   - A clear total price is displayed at the bottom, along with a prominent checkout button.

### Color Scheme

- The primary colors used are black, white, and a soft orange for the price tags and buttons.
- This color scheme ensures readability while maintaining a sophisticated appearance.

### Typography

- The app uses a combination of serif and sans-serif fonts to create a professional and stylish look.
- Titles are bold and large to attract attention, while product details are displayed in smaller, more subtle fonts.

## Data Storage Implementation

### Local Storage

- The app uses local storage to save the user's cart items.
- This approach ensures that the cart persists even if the user closes the app or refreshes the page.

### State Management

- State is managed using React’s built-in hooks.
- The `useState` hook manages the products in the cart and other user interactions.
- The `useEffect` hook ensures that the cart state is saved to local storage whenever it changes.

## Screenshots

### homepage and Cartscreen

![homescreen](screenshoots/screenshot.1.jpg)

### Checkout Page

![Checkout screen](screenshoots/screenshot.2.jpg)

