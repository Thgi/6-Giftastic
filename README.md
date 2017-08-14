# 6-Giftastic

This website is the first use of AJAX and REST protocols in order to access an API. This is an example using Giphy's API.

The website has a search box where you search for a specific animal that you want to find gifs for. 

Once you add it to the list, a button is generated with the animal you put in the search. When you click the button, the
website generates a list of GIF's relating to the animal. It also shows the rating of picture from general use to more
explicit images.

The GIF's are not animated at the time they are generated. Once you click on the image, then the GIF begins to animate. If the user wishes to disable it, then the user just clicks the image again and it becomes still.

In order to access the Giphy API, you need to use the following protocols in your Javascript:

$.ajax({
    url:queryURL,
    method: "GET"
  }).done(function(response) {
  
The queryURL is the URL you create based on what the user typed into the search box along with providing your API key. In order to use any API, you need an API key. The API key can be provided on the Giphy website.

The website also heavily uses Javascript and jQuery in order to manipulate the search results, create buttons, and enable and disable the GIF animations.
