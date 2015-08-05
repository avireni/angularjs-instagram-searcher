# AngularJS - Instagram Searcher

Instagram Searcher is a tool that allows users to search Instagram for pictures. It is built using AngularJS, Bootstrap, HTML5 and CSS3.

When users visit the page, they see the logo and a single text input where they are prompted to enter search term. When the user clicks submit, the app first validates the form to ensure that a tag was supplied.
On valid form submission, two things happen: An asynchronous query is made to the Instagram API for recent images tagged with the search term, and the view is rendered.

When the API results return, the app tells the user how many results were returned, and display the photos (if any).
User can navigate to the original photo on Instagram by clicking on any of the images that appear.

![Screenshot:](https://raw.githubusercontent.com/avireni/angularjs-instagram-searcher/gh-pages/assets/instagram.gif)
