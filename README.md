# Description
A development setup for the website Poe's Magazines. It uses Bootstrap, Grunt, Bower, Express, and Node. These are used to generate the content in 'public'. 

# Demo
The 'gh-pages' branch automatically creates a live site at http://literati.github.io/apc-bootstrap/public.

# Dependencies
Should be intalled in this order:

### Node & NPM
http://nodejs.org

### Grunt
    npm install -g grunt-cli

### Bower
    npm install -g bower

# Installation

To install for the first time:

	git clone git@github.com:literati/apc-bootsrap.git && npm install && grunt

# Usage
- Start the server: `node server`
- Edit code.
- test locally using express
- Merge gh-pages and master branches.
- View at http://literati.github.io/apc-bootstrap/public.

# To Do
- [x] Make splash page with main cover page
- [x] Update cover images
- [x] Replce LSU logo with "Poe's Magazine World"
- [x] Clean up google drive html files
- [x] Add google drive html to content folder
- [ ] Replace Express with Jekyll
- [ ] Make Jekyll bootstrap theme
- [ ] Add bootstap scrollspy and put all content on 1 page 
- [ ] Add panels to cover images
- [ ] Put google drive content into json format
- [ ] Serve json via handlebars.js or Jekyll equivalent


