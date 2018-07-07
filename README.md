# ATHLETICONS

* [Usage](#usage)
* [Setup](#setup)
* [Test Locally](#test-locally)
* [Thanks](#thanks)
* [Suggestions](#suggestions)


Icons
======

![alt text](https://raw.githubusercontent.com/marclanepitt/athleticons/master/icon-info.png)

Usage
=====

After following setup steps:
1. Use with unicode (codes found in image above^)
```html
<input type="text" value="&#xe902;" class="athleticons" />
```
* Don't forget to add the athleticons class with this method!

2. Use with class
```html
<span class="icon-tennis"></span>
```

Setup
======

1. Add fonts in font folder to your project
2. Add to css
style.css
```css
@font-face {
  font-family: 'athleticons';
  src:  url('path/to/athleticons.eot?h80q9d');
  src:  url('path/to/athleticons.eot?h80q9d#iefix') format('embedded-opentype'),
    url('path/to/athleticons.ttf?h80q9d') format('truetype'),
    url('path/to/athleticons.woff?h80q9d') format('woff'),
    url('path/to/athleticons.svg?h80q9d#athleticons') format('svg');
  font-weight: normal;
  font-style: normal;
}

[class^="icon-"], [class*=" icon-"] {
  /* use !important to prevent issues with browser extensions that change fonts */
  font-family: 'athleticons' !important;
  speak: none;
  font-style: normal;
  font-weight: normal;
  font-variant: normal;
  text-transform: none;
  line-height: 1;

  /* Better Font Rendering =========== */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.icon-tennis:before {
  content: "\e902";
}
.icon-soccer:before {
  content: "\e903";
}
.icon-badminton:before {
  content: "\e904";
}
.icon-curling:before {
  content: "\e905";
}
.icon-football:before {
  content: "\e906";
}
.icon-golf .path1:before {
  content: "\e907";
  color: rgb(0, 0, 0);
}
.icon-golf .path2:before {
  content: "\e908";
  margin-left: -0.7177734375em;
  color: rgb(0, 0, 0);
}
.icon-golf .path3:before {
  content: "\e909";
  margin-left: -0.7177734375em;
  color: rgb(0, 0, 0);
}
.icon-golf .path4:before {
  content: "\e90a";
  margin-left: -0.7177734375em;
  color: rgb(216, 216, 216);
}
.icon-golf .path5:before {
  content: "\e90b";
  margin-left: -0.7177734375em;
  color: rgb(0, 0, 0);
}
.icon-lax:before {
  content: "\e90c";
}
.icon-ping-pong:before {
  content: "\e90d";
}
.icon-rugby:before {
  content: "\e90e";
}
.icon-swim:before {
  content: "\e90f";
}
.icon-ultimate:before {
  content: "\e910";
}
.icon-volleyball:before {
  content: "\e911";
}
.icon-wrestling:before {
  content: "\e912";
}
.icon-archery:before {
  content: "\e913";
}
.icon-all-sports:before {
  content: "\e914";
}
.icon-baseball:before {
  content: "\e915";
}
.icon-basketball:before {
  content: "\e901";
}
.icon-hockey:before {
  content: "\e900";
}

.athleticons {
  font-family: 'athleticons' !important;
}
```

Test Locally
======

* Clone whole repository and open demo.html in browser

Special Thanks
======

[FontAwesome](https://fontawesome.com/icons?d=gallery) for inspiration and
[IcoMoon](icomoon.io) for generating this repository

Suggestions?
======

* Open up an issue with your icon suggestions