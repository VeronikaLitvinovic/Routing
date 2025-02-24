# README.md

This multi-page application is implemented using the React library and the `react-router-dom` library. The app uses an external API to fetch data and allows users to navigate to any page to view information about users, photo albums, and photos.

### `npm start`
Launches the application in development mode.
Open http://localhost:3000 to view it in a browser.

## API

The API used in this project is `https://jsonplaceholder.typicode.com/`.

## Pages

1. **User List Page**: This page displays the list of users in the system. Clicking on a user takes you to a page with detailed information about the user.

2. **User Details Page**: This page displays detailed information about the selected user, as well as a list of their photo albums. Clicking on an album takes you to the album page.

3. **Photo Album List Page**: This page displays a list of photo album titles. Clicking on an album takes you to the album page.

4. **Album Page**: This page displays the photos inside the album and information about the user who created the album. There should be a loading indicator while the album data is loading. Clicking on a username takes you to a page with detailed information about the user.

5. **404 Page**: This page is displayed when the path in the URL is not supported by the application. The page must have a link to return to the main page.

## Navigation

The application header contains two links:

- **Users**: Goes to the user list page.
- **Albums**: Goes to the photo albums list page.
