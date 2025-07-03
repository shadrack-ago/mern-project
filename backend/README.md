# Backend Setup

## Project Structure

- `models/` – Database schemas (e.g., Mongoose models)
- `routes/` – API endpoint definitions
- `controllers/` – Request handling logic
- `config/` – Configuration files (e.g., DB connection)
- `server.js` – Entry point for the backend server
- `.env` – Environment variables (e.g., DB URI, PORT)

## Getting Started

1. **Install dependencies:**
   ```sh
   npm install
   ```
2. **Set up environment variables:**
   - Create a `.env` file in the `backend/` directory with required variables (e.g., `PORT`, `MONGO_URI`).
3. **Run the server:**
   ```sh
   node server.js
   ```
   Or, for development with auto-reload:
   ```sh
   npx nodemon server.js
   ```

## Notes
- Ensure MongoDB is running and accessible via the URI in `.env`.
- Edit or add files in the respective folders as your app grows. 