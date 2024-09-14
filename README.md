# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

# React Jobs Website

This is a React.js application that was built as part of a React crash course. The application allows users to view job listings, create new job postings, and edit or delete existing ones.

## Key Concepts Learned

From this crash course, I have learned the following key concepts:

1. **Components**: Understanding the concept of components and how to create reusable UI elements.
2. **Props and State**: Learned how to pass data between components using props and how to manage the internal state of a component.
3. **React Hooks**: Gained knowledge of essential hooks like `useState` and `useEffect`, and how to use them to manage state and side effects.
4. **React Router**: Learned how to set up client-side routing using React Router, including creating dynamic routes and handling 404 pages.
5. **Data Fetching**: Implemented data fetching from a mock API using `fetch` and the `useEffect` hook, and learned how to handle loading and error states.
6. **React Styling**: Utilized Tailwind CSS for styling the application and learned how to dynamically apply classes based on component state.
7. **Form Handling**: Learned how to handle form submissions, including validating user input and updating the application state accordingly.
8. **CRUD Operations**: Implemented the full create, read, update, and delete (CRUD) functionality for the job listings.
9. **React Layouts**: Learned how to create and use layout components to provide a consistent structure and navigation across the application.
10. **React Data Loaders**: Utilized the data loader feature in React Router to fetch data for specific pages and pass it to the corresponding components.

## Running the Application

To run the application locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/mostafab50/react-jobs-website.git
   ```
2. Navigate to the project directory:
   ```
   cd react-jobs-website
   ```
3. Install the dependencies:
   ```
   npm install
   ```
4. Start the JSON server:
   ```
   npm run server
   ```
5. In a separate terminal, start the development server:
   ```
   npm run dev
   ```
6. Open your web browser and visit `http://localhost:3000` to see the application.

The application uses a mock API provided by the JSON server to handle the job data. The JSON server is running on `http://localhost:8000/api/jobs`.

## Deployment

To deploy the application, you can follow these steps:

1. Build the production-ready version of the application:
   ```
   npm run build
   ```
2. The generated `dist` folder contains the optimized, static files that can be deployed to a hosting service of your choice, such as Netlify, Vercel, or GitHub Pages.

## Additional Resources

- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [React Router Documentation](https://reactrouter.com/web/guides/quick-start)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [React Toastify Documentation](https://fkhadra.github.io/react-toastify/introduction)
- [JSON Server Documentation](https://github.com/typicode/json-server)

Feel free to explore the codebase and make any modifications or improvements to the application. If you have any questions or need further assistance, don't hesitate to reach out.