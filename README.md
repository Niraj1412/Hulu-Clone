# Hulu Clone

This is a Hulu clone web application built using React, TypeScript, and Vite. It leverages the [The Movie Database (TMDb) API](https://api.themoviedb.org/3/movie) to fetch movie data and display it in a user-friendly interface. The application is deployed on Vercel, allowing you to access it live.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Demo

You can access the live demo of the Hulu clone at [Vercel](https://hulu-clone-two-vert.vercel.app/).

## Features

- Browse a variety of movies and TV shows.
- View movie details such as title, overview, release date, and more.
- Filter movies by different categories (e.g., trending, top-rated, upcoming).
- Search for specific movies or TV shows.
- Responsive design for a seamless experience on various devices.

## Getting Started

To run this project locally, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/hulu-clone.git
   ```

2. Change into the project directory:

   ```bash
   cd hulu-clone
   ```

3. Install the project dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the project root and add your TMDb API key:

   ```env
   REACT_APP_TMDB_API_KEY=your-tmdb-api-key
   ```

   You can obtain an API key by signing up on the [TMDb website](https://www.themoviedb.org/documentation/api) (it's free).

5. Start the development server:

   ```bash
   npm run dev
   ```

   This will start the development server and open the app in your default web browser.

## Usage

Once the application is running locally, you can:

- Browse movies and TV shows from the homepage.
- Click on a movie or TV show to view its details.
- Use the category filters to explore different genres.
- Use the search bar to find specific movies or TV shows.

## Technologies Used

- React: A JavaScript library for building user interfaces.
- TypeScript: A statically typed superset of JavaScript.
- Vite: A fast, opinionated frontend build tool.
- [The Movie Database (TMDb) API](https://www.themoviedb.org/documentation/api): Provides access to a vast collection of movie and TV show data.
- Vercel: A cloud platform for hosting web applications.

## Contributing

Contributions to this project are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository on GitHub.
2. Clone your forked repository to your local machine.
3. Create a new branch for your feature or bug fix: `git checkout -b my-feature`.
4. Make your changes and commit them with descriptive commit messages.
5. Push your branch to your GitHub fork: `git push origin my-feature`.
6. Create a pull request from your forked repository to the original repository on GitHub.

Please make sure to adhere to the project's code of conduct and follow best practices when contributing.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
