# JSON Data Generator

![React](https://img.shields.io/badge/React-17.0.2-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-4.1-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![Node](https://img.shields.io/badge/Node-14.17.0-green)

This is a React application built with TypeScript and Vite. It generates a JSON file with fake data, with a maximum of 200 entries.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

1. **Clone the repository:**

   ```sh
   git clone https://github.com/SoroushGhodrat/data-generator.git
   ```

2. Navigate into the cloned repository:

   ```sh
   cd data-generator
   ```

3. Install the dependencies:

   ```sh
   npm install
   ```

4. Start the development server:
   ```sh
   npm run start
   ```

## Data Model

The application generates an array of data based on the following model:

```typescript
interface Data {
  _id: string;
  isAvailable: boolean;
  image: string;
  age: number;
  first_name: string;
  last_name: string;
  gender: string;
  email: string;
  position: string;
  office: string;
  phone: number;
  skills: string[];
  nationality: string;
  description: string;
}
```

## Features

- Generate fake JSON data
- Download data as a JSON file
- Copy data to clipboard
- Choose different themes for data display

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
