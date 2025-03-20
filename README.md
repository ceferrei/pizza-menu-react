# Bug-Free Pizza by Cecilia

<p align="center">
  <img src="public/pizza-menu-result.png" alt="Screenshot" width="400" />
</p>

This is a simple React project that displays a menu for a fictional pizzeria called "Bug-Free Pizza by Cecilia."

## Features

- Displays a pizza menu with name, ingredients, price, and image.
- Indicates if a pizza is sold out.
- Shows the pizzeria's opening hours.
- Allows placing an online order (simulated functionality).

## Technologies Used

- React (version 19.0.0)
- CSS

## Installation Guide

1. **Prerequisites:**

   - Make sure you have Node.js and npm (Node Package Manager) installed on your computer. You can download and install Node.js at [https://nodejs.org/](https://nodejs.org/). npm is automatically installed along with Node.js.

2. **Clone the repository:**

   ```bash
   git clone [https://github.com/ceferrei/pizza-menu-react.git](https://github.com/ceferrei/pizza-menu-react.git)
   ```

3. **Navigate to the project directory::**

   ```bash
   cd pizza-menu-react
   ```

4. **Install the dependencies::**

   ```bash
   npm install
   ```

   - This command will install all the project dependencies listed in the `package.json` file.

5. **Start the development server::**

   ```bash
   npm start
   ```

   - This command will start the React development server and open the project in your default browser at `http://localhost:3000`.

## Project Structure

pizza-menu-react/

```
├── public/
│ ├── index.html
│ └── ...
├── src/
│ ├── components/
│ │ ├── Header.js
│ │ ├── Menu.js
│ │ ├── Pizza.js
│ │ ├── Footer.js
│ │ └── Order.js
│ ├── pizzas/
│ │ ├── focaccia.jpg
│ │ ├── margherita.jpg
│ │ ├── spinaci.jpg
│ │ ├── funghi.jpg
│ │ ├── salamino.jpg
│ │ └── prosciutto.jpg
│ ├── App.js
│ ├── index.js
│ └── index.css
├── package.json
├── package-lock.json
└── README.md
```

## License

This project is licensed under the [MIT](https://opensource.org/licenses/MIT) license.
