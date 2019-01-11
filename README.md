
# JavaScript and DOM Manipulation

### Dataset

* [UFO Sightings Data](Data/data.js)


## Background

Use pure JavaScript, HTML, and CSS to create our web pages to visualize all recorded sightings from the website **www.ALIENS-R-REAL.com**. 


### Create an Automatic Table and Date Search
- Create a basic HTML web page.
- Using the ufo dataset provided in the form of a JavaScript object, we write a code that appends a table to our web page and then adds new rows of data for each UFO sighting.
- We made sure we have a column for `date/time`, `city`, `state`, `country`, `shape`, and `comment` at the very least.
- Add an `input` tag to our HTML document and we write JavaScript code that will search through the `date/time` column to find rows that match user input.

### Provide Multiple Search Categories
- Using multiple `input` tags and/or select dropdowns, we write JavaScript code so the user can to set multiple filters and search for UFO sightings using the following criteria based on the table columns: 

  1. `date/time`
  2. `city`
  3. `state`
  4. `country`
  5. `shape`

### Create Paginated Table
- We write a code that will paginate the table (client-side pagination) and only display a maximum set number of results at a time (e.g. 50 results per page). 
- We use [Bootstrap's Pagination Components](http://getbootstrap.com/components/#pagination) and write code to handle page changes and calculate the number of results which should appear on each page. 
