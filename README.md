<a name="readme-top"></a>

<div align="center">
  <h3 align="center">Frontend-Boilerplate</h3>
  <p>Using NPM-Scripts And GULP </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

You can save a lot of time by using a set of boilerplate files for your project instead of starting from scrach which can be a massive headache. Instead you can use the boilerplate to get started right away so you can focus on the main things for your project

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

In this boilerplate i used both tasks runner GULP version 4 and npm scripts to automated my common tasks. Tasks runner are configured to run the following functions

* Compile SCSS to css
* Beautify css and js
* Autoprefix and minify the CSS file
* Minify Js
* Minify Images
* Watch your SCSS and JS files directory and auto compile on changes
* Browser sync to auto reload browser after any changes

#### Directory structures for SASS

sass/
|
|– abstact/
|   |– function.scss    # Reusable functions
|   |– mixin.scss       # Mixix
|   |– variable.scss    # Variable
|   ...                 # Etc…
|
|– base/
|   |– animation.scss   # Animation style
|   |– base.scss        # Base
|   |– utilities.scss   # Utilities
|   |– typography.scss  # Typography rules
|   ...                 # Etc…
|
|– components/
|   |– buttons.scss     # Buttons
|   |– carousel.scss    # Carousel
|   |– card.scss        # Card
|   ...                 # Etc…
|
|– layout/
|   |– navigation.scss  # Navigation
|   |– grid.scss        # Grid system
|   |– header.scss      # Header
|   |– footer.scss      # Footer
|   |– sidebar.scss     # Sidebar
|   ...                 # Etc…
|
|– pages/
|   |– home.scss        # Home specific styles
|   ...                 # Etc…
|
|– vector/
|   |– tailwind.css   # third party
|   ...                # Etc…
|
|
`– main.scss             # Main Sass file

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

By following the instructions you can run the script on your machine

### Prerequisites

Before installing the script you need some external dependencies on your machine

* nodejs
  ```sh
  sudo apt install nodejs
  ```  
#### Gulp

* Gulp-cli
  ```sh
  sudo npm install gulp-cli -g
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/S4F4Y4T/Frontend-Boilerplate.git
   ```
#### Npm Script

  * Rename npm-package.json to package.json

#### Gulp

  * Rename gulp-package.json to package.json

3. Install the packages
   ```sh
   npm install
   ```

<!-- USAGE EXAMPLES -->
## Usage

Start the task runner by following commands

#### Npm Script

  ```sh
   npm run start
   ```
  
#### Gulp

  ```sh
   gulp
   ```

Task runner will auto compile and reload the browser when you make changes on html or dist directory

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
