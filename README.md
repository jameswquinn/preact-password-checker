# PasswordChecker

A secure and user-friendly password strength checker component built with Preact and zxcvbn.

## Features

- Real-time password strength evaluation
- Visual strength indicator
- Detailed suggestions for improving password strength
- Lightweight and performant
- Easy to integrate into existing projects

## Demo

[Link to live demo - replace with your actual demo link]

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/password-checker.git
   ```
2. Navigate to the project directory:
   ```sh
   cd password-checker
   ```
3. Install dependencies:
   ```sh
   npm install
   ```

## Usage

### Basic Usage

To use the `PasswordChecker` component in your Preact project:

1. Import the component:

   ```jsx
   import PasswordChecker from './components/PasswordChecker';
   ```

2. Use it in your JSX:

   ```jsx
   const App = () => (
     <div>
       <h1>Sign Up</h1>
       <PasswordChecker />
     </div>
   );
   ```

### Props

The `PasswordChecker` component doesn't require any props, but you can customize it with the following optional props:

- `minLength` (number): Minimum required password length (default: 8)
- `onChange` (function): Callback function that receives the current password and strength score

Example:

```jsx
<PasswordChecker 
  minLength={10} 
  onChange={(password, score) => console.log(password, score)} 
/>
```

## Development

To start the development server:

```sh
npm start
```

This will run the app in development mode. Open [http://localhost:8080](http://localhost:8080) to view it in the browser.

### Building for Production

To create a production build:

```sh
npm run build
```

This will generate optimized files in the `dist/` directory.

### Running Tests

To run the test suite:

```sh
npm test
```

### Linting and Formatting

To lint the code:

```sh
npm run lint
```

To format the code:

```sh
npm run format
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please ensure you update tests as appropriate and adhere to the existing coding style.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- [zxcvbn](https://github.com/dropbox/zxcvbn) for the password strength estimation
- [Preact](https://preactjs.com/) for the lightweight React alternative

## Contact

Your Name - [@yourtwitter](https://twitter.com/yourtwitter) - email@example.com

Project Link: [https://github.com/yourusername/password-checker](https://github.com/yourusername/password-checker)
