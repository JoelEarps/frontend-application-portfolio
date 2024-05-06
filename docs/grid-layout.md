# Grid Layout

CSS grid layout is method of layout out the page so it is divided into columns.

### Terminology

Grid Line - the dividing lines that make up the structure of the grid.
Grid Lane - the space between two adjacent gird lines.
Grid Area - the total area from 4 grid connecting grid lines.

## HTML Development

Will make a simple HTML that uses grid view and also has a carousel.

Using in built modules and plugins

### Basics

All documents start with `<!DOCTYPE hmtl>`
The html part has the html tag and then the visible part is in the body.
A divison i.e section of the html diagram can be defined by a div element.

### Grid View in HTML

When defining a grid view you can use the grid display style. From here you can then define how you want the grids to work.
This can be done by defining grid container rows properties.
This can be done with fractions etc or pixels - to make the fraction use easier you can use the repeat function to specify 6 colums each taking up a fraction - repeat(6, 1fr)

### Carousel in HTML

Bootstrap
JQuery
CDN

https://www.youtube.com/watch?v=EiNiSFIPIQE\

Styling

Heights

vH

getting screen dimensions

Selection colour on buttons

Pressing buttons html

Passing id to pressed buttons

Making a Nav Bar

Super simple
Make a div and then link with hyperlinks

Resizing elements on change - fluid design

Fetching Data

```
function getGithubProfileInformation(){
return fetch("https://api.github.com/users/JoelEarps")
.then(function (response) {
response.json();
})
.then(function (data) {
console.log(data);
})
.catch(function (err) {
console.warn("Something went wrong.", err);
});
}

return in a promise only passes the next promise to the
```

Running commands on load
