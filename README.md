# Sergio's Index
Sergio's personal page. Updated version of [Sergio's Personal Cabinet](https://gitlab.com/bbjprojek/cabinet). A lightweight and static html5 page for personal thoughts and posts.

## Serving
Install npm dependencies:
```
npm install
```
To serve the web right away:
```
npm run start
```

## Assets; stripped
In my desire to make a extremely lightweight and minimal html5 website (with pages around 8-36 kB without images), I had to divide stylesheets and scripts so this way I only add the necessary features for each HTML page.

The main stylesheets are:
* [main.css](/assets/main.css) is the main stylesheet which every page need, defined layout and colors
* [blog.css](/assets/blog.css) is the stylesheet for blog headings, featuring the box with the date, topic and title

Unlike with cabinet, this page doesn't use any javascript for now.
