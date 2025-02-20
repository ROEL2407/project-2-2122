# GitHub GraphQL API Portfolio website

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Paid attention](#paid-attention)
- [Installation](#installation)
- [Live Demo](#live-demo)
- [Checklist](#checklist)
- [Commits](#commits)
- [Resources](#resources)
- [License](#license)

## Description

A portfolio website built with the GitHub GraphQL. You can see all GitHub projects of a person and see more details about it.

Entree

![portfolio](https://user-images.githubusercontent.com/24413936/163160763-5486e7a6-471e-4d72-bb55-b5a521761966.png)

Details

![portfoliodetails](https://user-images.githubusercontent.com/24413936/163160790-4355db0f-072b-4c09-b010-0d3849248dbe.png)

## Features

This is app is a portfolio site where you can see all your GitHub repositories. You see your repository with a description on the homepage and the languages the code consists of. You have two buttons, one for the live demo and one to go to a detail page. On the detail page, you can read the README of that project. With the button at the top, you can pick a background color.

## Paid attention

While building this project, we paid extra attention that the site would be supported on all devices. We did this by adding support tags in our code.

Example

```css
@supports (display: flex) {
  header {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    padding: 1em 4em;
  }
}
```

## Installation

Clone this repository

```
https://github.com/ROEL2407/Github-GraphQL-API-portfolio.git
```

Install the packages

```
npm install
```

Start the app

```
npm start
```

## Live Demo

The website can be viewed live on [here](https://portfolio-website-roel.herokuapp.com/)

## Checklist

- [x] Show repo's
- [x] Detail of repo's
- [x] Language('s) of repo's
- [x] README in detail page displayed
- [x] Change color of webpage
- [x] Save changed color in localstorage
- [ ] Contact page with form
- [ ] About page
- [ ] Page with a form to fill the about page
- [ ] Login for admin purposes

## Commits

In this repo we will commit our work. To make this more visible for ourselves and others, we've added little headers to the commit titles:

- Created = a file is created
- Updated = updated a file or piece of code
- Delete = deleted a file

## Authors
Made by [Marloes Tacx](https://github.com/marloestacx) & [Roel Komen](https://github.com/ROEL2407)

## Resources

- [GitHub GraphQL API](https://docs.github.com/en/enterprise-server@3.4/graphql)
- [Markdown-it](https://www.npmjs.com/package/markdown-it)
- [Caniuse](https://caniuse.com)

### Credits

- Our teachers at the minor Web Development.
- Our fellow students who've helped us to resolve some problems and learn us new types of tricks.
- Stack Overflow for giving us the answers that we could tweak or that helped us understand our problem in the code better.
<hr />

## License

Usage is provided under the [MIT License](https://github.com/ROEL2407/Github-GraphQL-API-portfolio/blob/main/LICENSE). See LICENSE for the full details.

<!-- Here are some hints for your project! -->

<!-- Start out with a title and a description -->

<!-- Add a nice image here at the end of the week, showing off your shiny frontend 📸 -->

<!-- Add a link to your live demo in Github Pages 🌐-->

<!-- replace the code in the /docs folder with your own, so you can showcase your work with GitHub Pages 🌍 -->

<!-- Maybe a table of contents here? 📚 -->

<!-- ☝️ replace this description with a description of your own work -->

<!-- How about a section that describes how to install this project? 🤓 -->

<!-- ...but how does one use this project? What are its features 🤔 -->

<!-- ...you should implement an explanation of client- server rendering choices 🍽 -->

<!-- ...and an activity diagram including the Service Worker 📈 -->

<!-- This would be a good place for a list of enhancements to optimize the critical render path implemented your app  -->

<!-- Maybe a checklist of done stuff and stuff still on your wishlist? ✅ -->

<!-- We all stand on the shoulders of giants, please link all the sources you used in to create this project. -->

<!-- How about a license here? When in doubt use GNU GPL v3. 📜  -->
