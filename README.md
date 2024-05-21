# Guitar LA (With TypeScript) 

**Live Demo**: [Guitar LA Live](https://guitar-la-owenvassarotto.netlify.app/)

Guitar LA is a React application built with Vite, enabling users to manage a shopping cart for guitar purchases. Users can add, remove, and adjust quantities of guitars and see an updated total cost.

![image](https://github.com/owenvassarotto/guitar-la/assets/110845731/b38c742b-eb4a-4b8e-a363-48bab9e7fea4)

## Features

- **Add to Cart**: Add guitars with a click.
- **Adjust Quantity**: Increase or decrease guitar quantities in the cart.
- **Remove Items**: Remove guitars from the cart.
- **View Total**: Automatically updated total price.

## State Management with `useReducer`

The project leverages the `useReducer` hook for managing the state of the shopping cart. This approach provides a more scalable and maintainable solution for state management compared to `useState`, especially as the application's state logic becomes more complex.

### Benefits of `useReducer` in this Project

- **Predictable State Transitions**: State transitions are managed through a reducer function, making the logic predictable and easier to debug.
- **Better Organization**: Centralizes state management, reducing the need for multiple `useState` hooks and simplifying component logic.
- **Enhanced Scalability**: Simplifies adding new actions and state changes as the project grows.

## Quick Start

### Prerequisites

- Node.js installed on your machine.

### Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/owenvassarotto/guitarla-ts.git
   ```
2. Install dependencies:
   ```bash
   cd guitarla-ts
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## Built With

[![My Skills](https://skillicons.dev/icons?i=react,ts,css,vite)](https://skillicons.dev)

## Contributing

Contributions are welcome. Please follow this flow:
1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request