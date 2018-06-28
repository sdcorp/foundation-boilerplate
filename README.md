# Foundation boilerplate

This is the boilerplate for use with [Foundation for Sites](http://foundation.zurb.com/sites) and based on official [Foundation ZURB Template](https://github.com/zurb/foundation-zurb-template). It has a Gulp-powered build system with these features:
- HTML templates with Pug
- Sass compilation and prefixing
- JavaScript module bundling with webpack
- Built-in BrowserSync server
- For production builds:
  - CSS compression
  - JavaScript compression
  - Image compression
## Setup
1. **Install [Node 7.2.1 or greater](https://nodejs.org)**.
2. Clone the project.
    - HTTP:     `git clone git@github.com:sdcorp/foundation-boilerplate.git`
    - SSH:      `git@github.com:sdcorp/foundation-boilerplate.git`

## Installation

```bash
# Install the dependencies with yarn

$ yarn

or

# Install the dependencies with npm

$ npm install
```

### Run

For development:
```sh
$ npm run dev
```
Your finished site will be created in a folder called `dist`, viewable at this URL: `http://localhost:8000`

----
For production release:
```sh
$ npm run build
```