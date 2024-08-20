# Giphy List App

A simple React application to search and display GIFs using the Giphy API.

## Description

This application allows users to search for GIFs using the Giphy API. It displays a list of GIFs based on the search query entered by the user. The application consists of the following main components:

- **App**: The main component that handles the state and API calls.
- **SearchForm**: A component for the search input.
- **GifList**: A component to display the list of GIFs.

### App Component

The `App` component is the main component of the application. It manages the state and handles API calls to fetch GIFs based on the user's search query.

#### State Variables

- `gifs`: An array to store the fetched GIFs.
- `query`: A string to store the current search query. Initialized to "candy".
- `loading`: A boolean to indicate whether the data is being loaded.

#### useEffect Hook

The `useEffect` hook is used to fetch GIFs from the Giphy API whenever the `query` state changes. It uses Axios to make the API call and updates the `gifs` state with the fetched data. It also handles any errors that occur during the fetch.

#### handleQueryChange Function

The `handleQueryChange` function updates the `query` state with the new search text entered by the user.

## Installation

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```bash
    cd giphy-list-app
    ```
3. Install the dependencies:
    ```bash
    npm install
    ```

## Usage

1. Start the development server:
    ```bash
    npm start
    ```
2. Open your browser and navigate to `http://localhost:3000`.

## Components

- **App**: The main component that handles the state and API calls.
- **SearchForm**: A component for the search input.
- **GifList**: A component to display the list of GIFs.

## Dependencies

- React
- Axios

## API

This application uses the Giphy API to fetch GIFs. You can find more information about the API [here](https://developers.giphy.com/docs/api/endpoint#search).

## License

This project is licensed under the MIT License.