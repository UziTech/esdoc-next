<!--![Owner Status](https://img.shields.io/badge/owner-busy-red.svg)-->
![CI](https://github.com/esdoc-next/esdoc-next/workflows/CI/badge.svg)
[![Coverage Status](https://codecov.io/gh/esdoc/esdoc/branch/master/graph/badge.svg)](https://codecov.io/gh/esdoc/esdoc)
[![Document](https://doc.esdoc.org/github.com/esdoc/esdoc/badge.svg?t=0)](https://doc.esdoc.org/github.com/esdoc/esdoc)

# ESDoc

ESDoc is a documentation generator for JavaScript.<br/>
Please <a href="https://try.esdoc.org">try it out</a>!

<img class="screen-shot" src="https://raw.githubusercontent.com/esdoc/esdoc/master/manual/asset/image/top.png" width="500px" style="max-width: 500px; border: 1px solid rgba(0,0,0,0.1); box-shadow: 1px 1px 1px rgba(0,0,0,0.5);">

# Features
- Generates good documentation.
- Measures documentation coverage.
- Integrates test codes into documentation.
- Integrates manual into documentation.
- Parses ECMAScript proposals.

# Users
- [ESDoc](https://doc.esdoc.org/github.com/esdoc/esdoc/) (self-hosting &#x1F604;)
- [RxJS](http://reactivex.io/rxjs/)
- [Sketch API](http://developer.sketchapp.com/reference/api/)

And [more](https://github.com/search?o=desc&q=esdoc+filename%3Apackage.json+-user%3Ah13i32maru+-user%3Aesdoc+-user%3Aes-doc&ref=searchresults&s=indexed&type=Code&utf8=%E2%9C%93).

# Quick Start
* Move to a your project directory.  
  ```sh
  cd your-project/
  ```

* Install ESDoc and standard plugin.  
  ```sh
  npm install --save-dev esdoc esdoc-standard-plugin
  ```

* Create a configuration file.  
  ```sh
  echo '{
    "source": "./src",
    "destination": "./docs",
    "plugins": [{"name": "esdoc-standard-plugin"}]
  }' > .esdoc.json
  ```

* Run ESDoc.  
  ```sh
  ./node_modules/.bin/esdoc
  ```
* View the documentation.
  ```sh
  open ./docs/index.html
  ```

# Document
Please visit [esdoc.org](https://esdoc.org) to see more documentation.

## License
Copyright 2015 Ryo Maruyama - Permission granted under the [MIT license](LICENSE).
