# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and a snippet of the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact

https://catfact.ninja/

{
"current_page": 1,
"data": [
  {
    "fact": "Normal body temperature for a cat is 102 degrees F.",
    "length": 51
  },


1. A list of 150 random users in English.
https://randomuser.me/

{
"results": [
  {
    "gender": "male",
    "name": {
      "title": "mr",
      "first": "brad",
      "last": "gibson"
    },

1. All the repos on Github with Pursuit their name
https://github.com/search?q=pursuit&type=Repositories


1. All the JavaScript repos on Github with Pursuit in their name
https://github.com/search?l=JavaScript&q=pursuit&type=Repositories



1. All the Swift repos on Github with Pursuit in their name
https://github.com/search?l=Swift&q=pursuit&type=Repositories


1. A list of all Pokemon
https://pokeapi.co/
{
    "name": "ditto",
    "url": "https://pokeapi.co/api/v2/pokemon-form/132/"
  }
],
"game_indices": [
  {
    "game_index": 132,
    "version": {
      "name": "white-2",
      "url": "https://pokeapi.co/api/v2/version/22/"
    }
  },
  {
    "game_index": 132,
    "version": {
      "name": "black-2",
      "url": "https://pokeapi.co/api/v2/version/21/"
    }
  },


1. A list of all items in Fortnite
https://fortnite-api.theapinetwork.com/store/get
{
"data": [
    {
        "itemId": "2fad344-834e456-dcf643d-91f9712",
        "lastUpdate": 1553386039,
        "store": {
            "isFeatured": true,
            "isRefundable": true,
            "cost": "1500"
        },
        "item": {
            "name": "Beastmode",
            "description": "Gassed up and ready to roar.",
            "type": "outfit",
            "rarity": "epic",
            "images": {
                "icon": "https://fortnite-public-files.theapinetwork.com/outfit/c567e52c290292c99c7c9b44dd36827c.png",
                "featured": "https://fortnite-public-files.theapinetwork.com/featured/2fad344-834e456-dcf643d-91f9712.png",
                "background": "https://fortnite-public-files.theapinetwork.com/image/2fad344-834e456-dcf643d-91f9712.png",
                "information": "https://fortnite-public-files.theapinetwork.com/image/2fad344-834e456-dcf643d-91f9712/icon.png"
            },



1. A list of all Game of Thrones Episodes.


1. A list of all songs with "Love" in the title.

1. All information about Petyr Baelish from the Game of Thrones books
1. All the movies Leonardo Dicaprio has acted in

# Part Two

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200 
can see 200 when you use postman for a valid link
means nothing needs to be done and the data was retrieved successfully
1. 301
URL redirection (link has moved)
Can edit the link so the original link works instead of redirecting
1. 400
Invalid syntax (server was unable to process request)
To fix this, user will have to type in the correct request
1. 401
Unauthorized access
Needs login credients/ user privledge to access the data. If this was an app, I would login to access the data I want to see
1. 403 
GitHub 403 (forbidden access to client from server because I typed in an incorrect password too many times)
need to wait a bit before attempting to login again (nothing to do)
1. 404
Page on site could not be found on server
This means that the page has been deleted or moved (this is a client issue and will need to update proper url to gain access)
1. 418
https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/418
this is a reference error to a joke (I'm a teapot)?
indicates that the server refuses to brew coffee
1. 500
internal server error (server encountered a problem but cant give you specifics on what went wrong).

For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat



