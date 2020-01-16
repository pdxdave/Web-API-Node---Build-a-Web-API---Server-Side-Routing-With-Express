# Web-API-Node---Build-a-Web-API---Server-Side-Routing-With-Express
Web-API-Node---Build-a-Web-API---Server-Side-Routing-With-Express

### Routing
Q: What is routing?    
A: The routing engine in Express takes the HTTP method and the URL, puts them together,    
   maps them and puts them into a JavaScript function.  The "function" is the route 
   handler.
   
## Design process

- gather requirements    
- list of resources (nouns) [songs, users, pets]    
- list of endpoints

## Endpoints

- avoid using verbs. it's not a URL, it's a URI (e.g., /api/songs)    
- actions are expressed with http methods   

## Properties
- name
- duration
- artists
- year
- recordLabel

## Actions
- create  
- find a song by (filters)
- read
- update
- delete
- paginated list (filters)
- album art

|Action|Method|Endpoint|
|:--|:--|:--|
|List songs|GET|/api/songs|
|Create a song|POST|/api/songs|
|Update a song|PUT|/api/songs/:id|
|Remove a song|Delete|/api/songs/:id|
|Add Album Art|PUT|/api/songs/:id/cover|

## Common JS module system
- import a module using: require()
- export a module using: module.exports

## Query string
- [article about a url](https://deopud.co.uk/blog/anatomy-of-a-url)
- begins with a '?'
- is made upf of key=value pairs
- each key=value pair is separated by an '&'
- the query values are accessed in: req.query






