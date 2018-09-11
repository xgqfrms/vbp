# VUE


## CLI

```sh
# remove old version (1.x / 2.x)
$ npm uninstall vue-cli -g or yarn global remove vue-cli.

# install 3.x
$ npm install -g @vue/cli

# OR
$ yarn global add @vue/cli

# check version
$ vue --version
$ vue -V

# help
$ vue --help
$ vue -h

# app
$ vue create app
# dev
$ vue create dev

$ vue create --help

$ vue ui

```

https://cli.vuejs.org/guide/

## NVM

https://github.com/creationix/nvm
https://github.com/coreybutler/nvm-windows



## Prototyping

> You can rapidly prototype with just a single `*.vue` file with the `vue serve` and `vue build` commands

```sh

$ npm install -g @vue/cli-service-global

```

## vue plugins

```sh
# plugins

$ vue add @vue/eslint
# OR
$ vue add @vue/cli-plugin-eslint

$ vue add router
$ vue add vuex

$ vue add @vue/eslint --config airbnb --lintOn save


```

https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue

## Router

> HTML5 History

https://router.vuejs.org/guide/essentials/history-mode.html


## npx

https://router.vuejs.org/guide/essentials/history-mode.html

## .vuerc

```json
{
    "useConfigFiles": true,
    "router": true,
    "vuex": true,
    "cssPreprocessor": "sass",
    "plugins": {
        "@vue/cli-plugin-babel": {},
        "@vue/cli-plugin-eslint": {
            "config": "airbnb",
            "lintOn": ["save", "commit"]
        }
    }
}

```

## vue-cli-service

https://cli.vuejs.org/guide/cli-service.html#using-the-binary