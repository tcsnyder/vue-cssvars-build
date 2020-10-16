# vue-build-cssvars

## Summary

this is a bare project showing css variables in vue.

- all relavant code in `App.vue`
- build minimization turned off in `vue.config.js`
- running `yarn serve` shows the following page


![](docs/serve.png)

## Issue

When building for production, css vars do not get injected to the component
![](docs/build.png)

## odd behaviour
This issue occurs only in some environments I have listed details below.

##### Css variables do not work in build
`Machine 1`
```
os: Linux
kernel: 5.8.11
node-version: 14.14.0
yarn-version: 1.22.5
```