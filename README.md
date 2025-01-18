# Mango Go - Your Ultimate Manga Reading Website

Mango Go is a feature-rich manga reading website designed to deliver an unparalleled reading experience. With a sleek frontend powered by React and a robust backend built with Flask, Mango Go leverages web scraping to curate manga content seamlessly.

## Features

- **User-Friendly Interface**: Enjoy an intuitive and responsive design that adapts to all devices.
- **Extensive Manga Library**: Access a vast collection of manga titles across multiple genres.
- **Advanced Search**: Quickly find your favorite manga using title, author, or genre filters.
- **Bookmarking and Favorites**: Save and organize your favorite manga for easy access.
- **Dark Mode**: Switch between light and dark themes for a comfortable reading experience.

## Tech Stack

### Frontend:

- **React**: For a responsive and dynamic user interface.
- **CSS/SCSS**: For styling the application.
- **Axios**: For API communication between the frontend and backend.

### Backend:

- **Flask**: A lightweight Python web framework to manage API endpoints and business logic.
- **BeautifulSoup**: For web scraping manga content.
- **SQLite**: A lightweight database to store user data and bookmarks.

### Tools & Libraries:

- **React Router**: For seamless navigation.
- **Flask-CORS**: To enable secure communication between the frontend and backend.
- **Requests**: For efficient HTTP requests during web scraping.

## Installation

### Prerequisites:

- **Node.js** and **npm** installed for the frontend.
- **Python 3.8+** for the backend.

### Steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/mango-go.git
   cd mango-go
   ```

2. **Frontend Setup**:

   ```bash
   cd frontend
   npm install
   npm start
   ```

3. **Backend Setup**:

   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   python app.py
   ```

4. **Run the Application**:
   - The frontend will be available at `http://localhost:3000`.
   - The backend API will run at `http://localhost:5000`.

## Usage

1. Open the application in your browser.
2. Browse through the manga collection or use the search feature.
3. Click on a manga title to start reading.
4. Bookmark your favorite manga for easy access later.

## Project Structure

```
Mango-Go/
|-- frontend/
|   |-- src/
|   |   |-- components/
|   |   |-- pages/
|   |   |-- App.js
|   |-- public/
|-- backend/
|   |-- app.py
|   |-- scraper.py
|   |-- models.py
|   |-- templates/
|-- README.md
|-- requirements.txt
```

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

## License

Mango Go is open source and distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgements

- **React and Flask Communities** for their robust tools and documentation.
- **BeautifulSoup** for simplifying web scraping.
- **Manga Sources** for their amazing content.

---

Enjoy reading manga with Mango Go! If you encounter any issues or have suggestions, feel free to create an issue in the repository.
