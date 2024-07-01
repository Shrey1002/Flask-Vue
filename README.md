# Flask-Vue.js Game Library

A full-stack web application for managing a game library, built with Flask for the backend and Vue.js for the frontend. This project demonstrates how to create a Single Page Application (SPA) that performs CRUD (Create, Read, Update, Delete) operations.

## Features

- Add new games to the library
- View list of games
- Delete games from the library
- RESTful API with Flask backend
- Responsive frontend with Vue.js
- Vue Router for navigation
- Bootstrap for styling and modals

## Tech Stack

- Backend: Flask (Python)
- Frontend: Vue.js 2.x
- Routing: Vue Router
- Styling: Bootstrap
- API: RESTful

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.7+
- Node.js and npm
- Git

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/flask-vue-game-library.git
   cd flask-vue-game-library
   ```

2. Set up the backend:
   ```
   cd backend
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```

3. Set up the frontend:
   ```
   cd ../frontend
   npm install
   ```

## Usage

1. Start the Flask backend server:
   ```
   cd backend
   flask run
   ```

2. In a new terminal, start the Vue.js development server:
   ```
   cd frontend
   npm run serve
   ```

3. Open your web browser and navigate to `http://localhost:8080`

## Project Structure

```
flask-vue-game-library/
│
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   └── venv/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── views/
│   │   ├── App.vue
│   │   ├── main.js
│   │   └── router.js
│   ├── package.json
│   └── vue.config.js
│
└── README.md
```

## API Endpoints

- `GET /games`: Retrieve all games
- `POST /games`: Add a new game
- `DELETE /games/<id>`: Delete a game by ID

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Original code by Michael Herman from [TestDriven.io](https://testdriven.io/)
- Flask: https://flask.palletsprojects.com/
- Vue.js: https://vuejs.org/
- Bootstrap: https://getbootstrap.com/
