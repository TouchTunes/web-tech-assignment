# TouchTunes Web Assignment

Congratulations! You have been assigned this exercise because we want to evaluate your technical skills and experience.

We want you to build a basic Spotify application with the following specs:

# Product Specifications

Using the  Spotify API , your application should let a user search for an artist to retrieve information
about his/her albums. Refer to the wireframes for visuals.

## A. Landing Page - Login With Spotify

1. The landing page of your application contains a “Login with Spotify” button
2. Clicking on the button starts the [Spotify Implicit Grant](https://developer.spotify.com/documentation/general/guides/authorization-guide/#implicit-grant-flow) authentication flow
3. Upon successful authentication, the user is redirected to the “Artist Search” page

## B. Artist Search

1. The page contains a search input with placeholder text: “Search for an artist...”
2. When pressing the “Return” key inside the search box, the user is presented with the results
    - Spotify artist search: https://developer.spotify.com/console/get-search-item
4. __Bonus__: Implement a “search-as-you-type” functionality

## C. Browsing Artists
  1. Displays the results from (B)
  2. The results should respect the visuals presented on page 3 of the wireframes, and the following specifications:
      - Keep the Spotify API ordering
      - Display an artist image
      - Display the artist’s popularity as a star rating (1-5 stars)
      - Display the number of followers for that artist
      - Can be clicked to retrieve that artist’s album

## D. Browsing Artist Albums
1. Displays the albums for the artist clicked in (C)
    - Spotify artist album search: https://developer.spotify.com/console/get-artist-albums/
2. The results should respect the visuals presented on page 4 of the wireframes, and the following specifications:
    - Keep the Spotify API ordering
    - Display the album’s cover image
    - Display the name of the album
    - Display the list of artists included on the album
    - Display the album’s release year
    - Display the total number of tracks on the album
    - Display a clickable link that opens a new tab to the Spotify preview of that album.
    __Hint:__ Use the the "external_urls:" parameter from the api results.
3. Clicking on the back button of the browser returns to the previous search results in (C)

# Technical Specifications

- Your application should be a single-page application written in [React](https://reactjs.org) .
- You can use  [Create React App](https://create-react-app.dev/) to get started
- You can use a CSS framework or a React UI library for the design of your application
- Your application should be responsive, i.e. it should adapt seamlessly to different
devices

# Things We Will Be Looking For

- The app works and respects the specs
- Your code demonstrates good knowledge of the React API and its core concepts
- Your application’s UX is clean and consistent
- You can explain your technical choices and walk us through your codebase

# Deliverable

A link to your public Github repository with instructions to build/run it.

Good luck!

__Resources:__
- [Wireframes](/wireframes.pdf)
- [Spotify API tutorial](https://developer.spotify.com/documentation/web-api/quick-start/)
