# {{ name }}

> {{ description }}

## Build Setup

``` bash
# install dependencies with Yarn (yarnpkg.com)
yarn

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
{{#unit}}

# run unit tests
npm run unit
{{/unit}}
{{#e2e}}

# run e2e tests
npm run e2e
{{/e2e}}
{{#if_or unit e2e}}

# run all tests
npm test
{{/if_or}}
{{#element}}

# regenerate Element component styles in theme/ from element-variables.css
npm run theme
{{/element}}
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
