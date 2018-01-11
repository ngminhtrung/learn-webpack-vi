[![Code Climate](https://codeclimate.com/github/danderu/learn-webpack/badges/gpa.svg)](https://codeclimate.com/github/danderu/learn-webpack)

# Learn Webpack
[Webpack](https://webpack.github.io/) helps you managing dependencies in your project, and also offers a friendly and fast development environment, simplifying a lot of common tasks behind a simple configuration file. 

It also allows you to bundle your modules into static assets for browsers. Its killer feature is the known as hot module replacement, which lets your live code in the browser update automatically as you change files in your preferred editor without a page reload.

Unfortunately, webpack doc pages are not friendly enough for beginners like me. That's why I decided to create this repository: to help people to learn webpack with a collection of exercises and examples.

## How to use this repository
First of all, clone or fork this repository. If you are not used with npm or git, This is what you basically need to do:

The examples in this repository use [yarn](https://yarnpkg.com/en/) as dependecy package manager, to take advantage of yarn's cache, since most of them reuse the same dependencies. In the examples it is assumed that you've already [installed yarn](https://yarnpkg.com/en/docs/install), although it's not mandatory. You could always do `npm install` to install the dependencies in every example.

```
git@github.com:ngminhtrung/learn-webpack-vi.git
cd learn-webpack
cd examples/một_ví_dụ_nào_đó
npm install
```

If you need more information about forking a repository, follow this [guide](https://help.github.com/articles/fork-a-repo/).

## Danh sách các ví dụ
Navigate into the example folders to find out the different webpack configuration examples to help you get started with this module bundler. You will learn about the different configuration possibilities, from the simplest one to the most advanced configuration for deploying into production your bundles.

* [Example 1: Hello world! with Webpack](https://github.com/ngminhtrung/learn-webpack-vi/tree/master/examples/01-hello-webpack)
* [Example 2: Multiple entries](https://github.com/ngminhtrung/learn-webpack-vi/tree/master/examples/02-multiple-entries)
* [Example 3: Loaders](https://github.com/ngminhtrung/learn-webpack-vi/tree/master/examples/03-loaders)
* [Example 4: Styles](https://github.com/ngminhtrung/learn-webpack-vi/tree/master/examples/04-styles)
* [Example 5: Chunks](https://github.com/ngminhtrung/learn-webpack-vi/tree/master/examples/05-chunks)
* [Example 6: Vendors](https://github.com/ngminhtrung/learn-webpack-vi/tree/master/examples/06-vendors)
* [Example 7: Development environment setup](https://github.com/ngminhtrung/learn-webpack-vi/tree/master/examples/07-development-environment-setup)
* [Example 8: Optimizations for production](https://github.com/ngminhtrung/learn-webpack-vi/tree/master/examples/08-optimizations-for-production)

## How to collaborate
Please feel free to propose new examples or ask for help with any configuration you are trying to learn.

## License
MIT
