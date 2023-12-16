Develop an application based on video-on-demand websites that provides an extensive database of available content. It should consist of various pages and a global navbar.

- Popular Movies Page (Home Page)
- Top Rated Movies Page
- Upcoming Movies Page
- Single Movie Details Page
- Searched Movies Page

<br/>
### List of Features

#### Global Navbar:

- Users should be able to see a navbar at the top of every page.
- Users should be able to see the title “movieDB” at the left side of the navbar.
- Users should be able to view navigation buttons, including Popular, Top Rated, and Upcoming, in the navbar.
- Users should be able to navigate to Popular (`/`), Top Rated (`/top-rated`), and Upcoming (`/upcoming`) Routes by clicking on the respective buttons.
- Users should be able to see a search bar and a search button inside the navbar, where they can enter their search queries.

#### Popular Movies Page (Home Page):

- Users should be able to view a grid of movie posters, arranged in multiple rows and columns, fetched from the **popular movies API**.
- Each movie poster should include an image of the movie, its name, its rating, and a `View Details` button.

#### Top Rated Movies Page:

- Users should be able to view a grid of movie posters, arranged in multiple rows and columns, fetched from the **top rated movies API**.
- Each movie poster should include an image of the movie, its name, its rating, and a `View Details` button.

#### Upcoming Movies Page:

- Users should be able to view a grid of movie posters, arranged in multiple rows and columns, fetched from the **upcoming movies API**.
- Each movie poster should include an image of the movie, its name, its rating, and a `View Details` button.

#### Single Movie Details Page:

- When users click on the `View Details` button of a specific movie poster on any movie page, it should open a new page displaying the details of the respective movie.
- Users should be able to see two sections:
  - Movie details section
  - Cast details section
- The movie details section should include the movie's name, image, ratings, duration, genre, release date, and an overview, all of which will be fetched from the **movie details API**.
- The cast details section should display a grid of cast members, arranged in multiple rows and columns, retrieved from the **movie cast details API**.
- Each cast member's details should include their image, their original name, and their character name in the movie.

#### Searched Movies Page:

- The searched movies page should only be displayed when a search is initiated.
- Users should be able to view a grid of movie posters, arranged in multiple rows and columns, fetched from the **searched movies API**.
- Each movie poster should include an image of the movie, its name, its rating, and a `View Details` button.

**Note:**

- Every page should feature a global nav bar at the top.
- Initially, users should be able to see the Popular Page (Home Page) upon accessing the website.
- Each page corresponds to a different route.

### Instructions:

- Upload the project on Codesandbox (https://codesandbox.io/) and submit it using the code sandbox link. This is mandatory, without this, the submission will not be accepted.
- The project must be responsive with decent CSS.
- It is not necessary that the colors should match the images above. Use your imagination and try to make it as you like.
- Pagination is required.
- If you are a candidate with more than 6 months of experience then using Redux for state management purposes is a MUST.
- If you are a fresher then can directly do API calls in the components themselves.
- Make sure the components are reusable wherever possible.

### API Details:

- You should generate your own `API_KEY` by visiting https://www.themoviedb.org/documentation/api

- Follow the below reference to build an image URL [https://developer.themoviedb.org/docs/image-basics](https://developer.themoviedb.org/docs/image-basics)

### APIs

- Get popular Movies:

```api
https://api.themoviedb.org/3/movie/popular?api_key=${API_KEY}&language=en-US&page=1
```

- Get Top Rated Movies:

```api
https://api.themoviedb.org/3/movie/top_rated?api_key=${API_KEY}&language=en-US&page=1
```

- Get Upcoming Movies:

```api
https://api.themoviedb.org/3/movie/upcoming?api_key=${API_KEY}&language=en-US&page=1
```

- Get Single Movie Details:

```api
https://api.themoviedb.org/3/movie/${MOVIE_ID}?api_key=${API_KEY}&language=en-US
```

- Get Movie Cast Details:

```api
https://api.themoviedb.org/3/movie/${MOVIE_ID}/credits?api_key=${API_KEY}&language=en-US
```

- Get Searched Movies:

```api
https://api.themoviedb.org/3/search/movie?api_key=${API_KEY}&language=en-US&query=${MOVIE_NAME}&page=1
```

<br/>
**Note:** Make sure to replace `${API_KEY}`, `${MOVIE_ID}` and `${MOVIE_NAME}` with actual values when using these APIs.

<br/>
#### Submission Form:

<center>Click the below button and submit your code sandbox link</center>
<br>
<a target=_blank_ href="https://forms.ccbp.in/project-submission-form-project2">
  <center><button style="color: #fff; border: none; cursor: pointer; width: 218px; height: 34px; background-color: rgb(22, 101, 216); border-radius: 5.4px; box-shadow: rgb(0 0 0 / 36%) 0px 2px 4px 0px;font-family: Inter;font-size: 14px;color: rgb(255, 255, 255);font-weight: 500;letter-spacing: 0.5px;text-transform: uppercase;">
    SUBMIT
  </button>
  </center>
</a>

<br/>
<center>**Follow the clean code guidelines**</center>
