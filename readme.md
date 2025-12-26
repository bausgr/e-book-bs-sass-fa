## Features

- Modern layout with custom colors/styles/backgrounds
- Responsive design
- Sticky navbar with style changes on scroll
- Bootstrap modals
- Form & input styles
- Testimonials
- Contact page with Google Map

## Usage

This website is built with [Bootstrap](https://getbootstrap.com/) and [Sass](https://sass-lang.com/). It uses [Font Awesome](https://fontawesome.com/) for icons.

## Pattern to create sections:

<section id="details" class="details my-5">
      <div class="container">
        <div class="row">
          <div class="col-lg-x">...</div>
          <div class="col-lg-(12-x)">...</div>
        </div>
      </div>
</section>

## Deploy

- Create new repository @ Github
  git init
  git add .
  git commit -m "first commit"
  git branch -M main
  git remote add origin https://github.com/bausgr/e-book-bs-sass-fa.git
  git push -u origin main

You can add Bootstrap variables to the `bootstrap.scss` file.
You can look at the file `node_modules/bootstrap/dist/scss/_variables.scss` for a list of all the variables.
Do NOT edit the `variables.scss` file directly, as it will be overwritten when you update Bootstrap.

To add your own custom styles, use the `styles.scss` file.
