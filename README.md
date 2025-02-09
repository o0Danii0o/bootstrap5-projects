# Global Repository for Bootstrap 5 Projects

Welcome to my collection of **Bootstrap 5** projects! This repository serves as a central hub for various projects I’ve built using Bootstrap 5, showcasing different functionalities, design layouts, and features.

Each project below demonstrates the versatility and responsiveness of **Bootstrap 5**, a powerful front-end framework for building modern web applications.

## Table of Contents

Here’s a list of the available Bootstrap 5 projects in this repository:


- [E-book Website repository](https://github.com/o0Danii0o/ebook-website)
- [Vera Website (Software Solution) repository](https://github.com/o0Danii0o/vera-website)

Each of these projects is contained in its own repository, and you can explore them individually by clicking on the links above.

## Usage

To run any of the websites, open the following links:

- [E-book Website](https://ebook-website-six-tan.vercel.app/)
- [Vera Website (Software Solution)](https://vera-website-rust.vercel.app/)

Follow the instructions below to run it locally on your machine.

### Prerequisites

These websites are built with [Bootstrap](https://getbootstrap.com/) and [Sass](https://sass-lang.com/). They use [Font Awesome](https://fontawesome.com/) for icons.

In order to customize these websites, you need to install [Node.js](https://nodejs.org/en/). Then, clone the repository and run:

```bash
npm install
```

This will install Bootstrap, Sass and Font Awesome. To build your CSS files from Sass, run:

```bash
npm run sass:build
```

To watch your Sass files for changes, run:

```bash
npm run sass:watch
```

You can add Bootstrap variables to the `bootstrap.scss` file. You can look at the file `node_modules/bootstrap/dist/scss/_variables.scss` for a list of all the variables. Do NOT edit the `variables.scss` file directly, as it will be overwritten when you update Bootstrap.

To add your own custom styles, use the `styles.scss` file.
