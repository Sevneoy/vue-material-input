# vue-material-input

[![Build Status](https://travis-ci.org/wemake-services/vue-material-input.svg?branch=master)](https://travis-ci.org/wemake-services/vue-material-input) [![Coverage Status](https://coveralls.io/repos/github/wemake-services/vue-material-input/badge.svg?branch=master)](https://coveralls.io/github/wemake-services/vue-material-input?branch=master)

Simple implementation of Material Input with no dependencies.

## Showcase

![Showcase](https://raw.githubusercontent.com/wemake-services/vue-material-input/screenshots/vue-material-input.gif)

## Installation

```bash
npm install vue-material-input
```

## Usage

Example with `v-model`:

```javascript
import Vue from 'Vue'
import MaterialInput from 'vue-material-input'

const vm = new Vue({
  el: '#app', // note that `#app` must be presented in the html
  template: (
    '<form><p>Hello, {{ username }}</p>' +
      '<MaterialInput name="name" v-model="username">Your name</MaterialInput>' +
    '</form>'
  ),
  data () {
    return {
      username: 'admin'
    }
  },
  components: {
    MaterialInput
  }
})
```

For more examples, please check `/dev` folder and the [project's website](http://wemake.services/vue-material-input).
