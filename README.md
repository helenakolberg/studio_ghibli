# studio_ghibli  

A Vue application displaying information about Studio Ghibli films, using the Studio Ghibli API and a Google Chart.  

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).  
  
  
  
## Brief  

Your task is to create an application that makes a request to an API and displays the data.

Suggested APIs:

1. Studio Ghibli: https://ghibliapi.herokuapp.com/
2. Reddit: (Append `.json` to any Reddit URL - for example https://www.reddit.com/r/javascript.json)
3. Guardian search: https://content.guardianapis.com/search?q=brexit&format=json&api-key=test


These APIs all allow browser requests without authentication or keys. (In the case of the Guardian, `api-key=test` should be sufficient.)

There is a more extensive list of public APIs [here](https://github.com/public-apis/public-apis) that have varying degrees of accessibility. If you choose to use a different API, make sure you are able to load the data into your application without issue, so that you can spend the time focussing on building your application. We suggest you do not use an API that requires authentication (OAuth), though using an API which requires a key is fine, as long as you are able to get a key quickly and easily.

### MVP

- The application should display data from an API request.
- The application should have a clear separation of concerns (multiple components)
- Take input from the user to update the page. You could update the page by filtering or manipulating the data on user interaction, or you might make further API requests to load more data that is then displayed.

### Extensions

Looking into a library to visual the data.

- [Leaflet](https://leafletjs.com/) is an open-source library for rendering maps
- [Google Charts](https://developers.google.com/chart/) is a library for rendering charts and graphs
- [Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial) is a drawing surface for JavaScript.

You will need to use the library's documentation to integrate it into your application.
