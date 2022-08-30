# swapi

### A project diving into connecting React.js front-end applications with back-end APIs utilizing the Star Wars API aka swapi from https://swapi.dev/api/films.

---

-- 30 Aug 2022--

- Data fetch now takes place as soon as page loads in addition to on demand without creating an infinite loop.

- Application now retrieves from swapi and would post to a firebase backend, if plugged in. As it requires a google account I am omitting it for now.
- Fetch api used to define a request instead of default 'GET'
- ***

  -- 29 Aug 2022--

- Http request error handling basics implemented.

---

-- 27 Aug 2022--

- Began project utilizing asynchronous es6 for our http call with Fetch API
  (https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
- Application is currently reaching out to Star Wars API (swapi https://swapi.dev/) and populating fields as desired. Messages built in for loading and if no movies found.
