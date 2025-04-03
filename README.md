# Smart Nutrition

Smart Nutrition is a web-based system that helps users track and manage their nutritional intake efficiently. It is built with **Node.js** for the backend and **MySQL** for the database.

## Features
- User authentication and git bprofile management
- Food database with nutritional information
- Meal tracking and calorie calculation
- Personalized nutrition recommendations
- Data visualization and reports

## Tech Stack
- **Backend:** Node.js (Express.js)
- **Database:** MySQL
- **Authentication:** JWT (JSON Web Token)
- **API Communication:** RESTful API using Axios/Postman for testing

## Installation

### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [mongodb](https://www.mongodb.com/)

### Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/smart-nutrition.git
   cd smart-nutrition
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Configure the database:
   - Create a MySQL database named `smart_nutrition`.
   - Import the database schema from `database/schema.sql`.
   - Update `config/db.js` with your MySQL credentials.

4. Start the backend server:
   ```sh
   npm start
   ```
   The server will run on `http://localhost:5000` by default.

## API Endpoints
### User Authentication
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Authenticate and get a token

### Nutrition Data
- `GET /api/nutrition` - Fetch all nutritional data
- `POST /api/nutrition/add` - Add a new food item

### Meal Tracking
- `POST /api/meal` - Log a meal entry
- `GET /api/meal/:userId` - Get a user's meal history

## Future Improvements
- Add machine learning for personalized diet plans
- Implement a mobile-friendly UI
- Integrate barcode scanning for food items

## License
This project is licensed under the MIT License.

---
### Contributors
- **Jan Khalil Dela Cerna** (Developer)

