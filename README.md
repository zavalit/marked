# section-marked

a fork of npm's **marked** package, that puts content with a ```<h{1...6}/>``` tag in a ```<section />```

## Install

``` bash
npm install section-marked --save
```

## Usage

Example setting sections for ```h2``` header:

```js
var marked = require('marked');
marked.setOptions({
  section_depth: 2
});

```
