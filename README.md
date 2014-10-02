# VCUarts Travel Presentation

Built with reveal.js [![Build Status](https://travis-ci.org/hakimel/reveal.js.png?branch=master)](https://travis-ci.org/hakimel/reveal.js)

## Releases

coming real soon
__

### Installation

The **basic setup** is for authoring presentations only. The **full setup** gives you access to all reveal.js features as well as the development tasks needed to make changes to the source.

### Basic setup

The core of reveal.js is very easy to install. You'll simply need to download a copy of this repository and open the index.html file directly in your browser.

1. Download the latest version of reveal.js from <https://github.com/hakimel/reveal.js/releases>

2. Unzip and replace the example contents in index.html with your own

3. Open index.html in a browser to view it


### Full setup

Some reveal.js features, like external markdown, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the reveal.js repository  
```
$ git clone git@github.com:hakimel/reveal.js.git
```

5. Navigate to the reveal.js folder 
```
$ cd reveal.js
```

6. Install dependencies  
```
$ npm install
```

7. Serve the presentation and monitor source files for changes  
```
$ grunt serve
```

8. Open <http://localhost:8000> to view your presentation


### Folder Structure
- **css/** Core styles without which the project does not function
- **js/** Like above but for JavaScript
- **plugin/** Components that have been developed as extensions to reveal.js
- **lib/** All other third party assets (JavaScript, CSS, fonts)



## License

MIT licensed

Copyright (C) 2013 Hakim El Hattab, http://hakim.se
