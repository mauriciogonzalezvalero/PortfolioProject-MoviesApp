# Movies App

A responsive React-based web application that allows users to browse and discover movies, filter them by genre and rating, search by title, and manage a personal watchlist.

## Features

- **Browse Movies**: View a grid of movie cards with title, genre, and rating information
- **Search Functionality**: Search for movies by title
- **Filter Options**: Filter movies by:
  - Genre (Action, Drama, Fantasy, Horror)
  - Rating (Good, Ok, Bad)
- **Watchlist Management**: Add or remove movies from your personal watchlist
- **Responsive Design**: Optimized for both desktop and mobile viewing

## Tech Stack

- React.js
- React Router for navigation
- CSS for styling

## Getting Started

### Prerequisites

- Node.js and npm installed

### Installation

1. Clone the repository
2. Navigate to the project directory
3. Install dependencies:
   ```
   npm install
   ```
4. Start the development server:
   ```
   npm start
   ```
5. Open your browser and go to `http://localhost:3000`

## Usage

- The home page displays a grid of available movies
- Use the search bar to find specific movies by title
- Use the filter dropdowns to narrow down movies by genre or rating
- Click the toggle switch on any movie card to add it to your watchlist
- Navigate to the Watchlist page to view your selected movies

## Data Structure

The application uses a `movies.json` file that contains an array of movie objects, each with:

- `id`: Unique identifier
- `title`: Movie title
- `image`: Image filename
- `genre`: Movie genre
- `rating`: Numeric rating (scale of 1-10)

## License

This project is created for educational and portfolio purposes.
