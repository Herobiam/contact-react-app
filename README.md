
# Contact Management React App

This is a simple React application for managing contacts. The app allows users to create, list, and delete contacts with details such as name, surname, and email.

## Features

- **List Contacts**: View all contacts with their name, surname, and email.
- **Add Contact**: Add a new contact with basic details.
- **Delete Contact**: Remove a contact from the list.

## Getting Started

### Prerequisites

To run this project, you need to have Node.js and npm installed. You can download them from [here](https://nodejs.org).

### Installation


1. Install the dependencies:

   ```bash
   npm install
   ```

### Running the Application

To start the development server, run:

```bash
npm start
```

This will run the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### Build for Production

To create an optimized production build, run:

```bash
npm run build
```

### Testing

You can run the tests using the following command:

```bash
npm test
```

## API Integration

This app uses a simple mock API for fetching and managing contacts. The API calls are simulated using the `ContactsAPI` module located in the `src/utils/ContactsAPI.ts`.

## Project Structure

- **src/components**: Contains the main components of the app such as `ListContacts` and `CreateContact`.
- **src/utils**: Contains utility files like `ContactsAPI.ts` which simulate API interactions.
- **src/index.tsx**: Entry point of the application.

## Routes

- `/`: Home page where the list of contacts is displayed.
- `/create`: Page for adding a new contact.

## React Router

The application uses `react-router-dom` for routing. Make sure you are using version 6 or later.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
