# Travel Site

A hands-on project from [Udemy: Git a Web Developer Job: Mastering The Modern Workflow](https://www.udemy.com/git-a-web-developer-job-mastering-the-modern-workflow/learn/v4)

## [Live Demo](https://rubychi.github.io/udemy-travel-site/)

You can see a complete working example [here](https://rubychi.github.io/udemy-travel-site/)

## Features

* Desktop sticky header

* Revealing elements on scroll

* Lazy loading images for faster page loads

* Smooth scrolling to anchor links

* Hamburger menu animation

* Responsive web design (RWD): mobile-first approach, responsive images

* Support for responsive images and svg icons in legacy browsers

### Custom Features

* Add scroll to top feature

## Getting Started

Follow the instructions below to set up the environment and run this project on your local machine

### Prerequisites

* Node.js

### Installing

1. Download ZIP or clone this repo
```
> git clone https://github.com/rubychi/udemy-travel-site.git
```

2. Install dependencies via NPM
```
> npm install
```

3. Install gulp package globally to execute gulp command on your machine
```
> npm install gulp -g
```

4. Start the website
```
> gulp watch
```

5. See it up and running on http://localhost:3000

### Alternatively, build a production version of the website (all files will be put inside the folder docs)
```
> gulp build
```

## Built With

### Frontend

* jquery
* jquery-smooth-scroll
* waypoints
* lazysizes
* picturefill
* gulp
* normalize.css
* postcss
* webpack

## Course Notes

* CSS architecture: this project follows B.E.M rules for creating class names and writing css selectors

  * B: Block - an independent, reusable part of the design
  * E: Element - belongs to a block and cannot be used outside of the block it belongs to
  * M: Modifier - can be used on a block or an element to indicate a change to the default state of an object