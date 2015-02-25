# SIS Custom

Custom JavaScript, CSS & images for the SIS project

## Installation

1. Clone the repository

    ```bash
    git clone https://github.com/christianv/sis-custom.git
    cd sis-custom
    ```

1. Install the dependencies

    ```bash
    npm install
    npm install -g gulp
    ```

1. Run the build

    ```
    gulp
    ```

## Apply the changes to SIS

How to update a PeopleSoft SIS environment with custom files.

### Create output files

Running the `gulp` command will create the `dist` directory with the following files:

* A single CSS file: `dist/uc_sis.css`
* A single JavaScript file: `dist/uc_sis.js`
* Optimized images under: `dist/uc_images`

### CSS



## Styleguides & rules

* [JavaScript](docs/styleguides/javascript.md)
* [CSS](docs/styleguides/css.md)
* [Images](docs/styleguides/images.md)
