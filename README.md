[![npm version][npm-version-image]][npm-version-url]
[![npm downloads][npm-downloads-image]][npm-downloads-url]
[![Build Status][travis-image]][travis-url]
[![Demo][demo-image]][demo-url]
[![License][license-image]][license-url]

***

# FTI Group Icon Font

> Icon font for projects of FTI Group.

This [demo page][demo-url] will show all icons of the latest version 
of this package.


## Usage

There are different ways to use this font ...

### npm package

If you want to use the npm package just install with [npm](https://www.npmjs.com/)
                                                
```sh
$ npm install @tourstream/fti-group-icon-font --save
```

or with [yarn](https://yarnpkg.com/lang/en/)

```sh
$ yarn add @tourstream/fti-group-icon-font
```

After this step you can use the sources as you like. They can be found in `./node_modules/@tourstream/fti-group-icon-font/dist`

📌 **npm include only versioned packages.**


### link the source - CDN at Google Cloud Storage (GCS)

You can put the following snippet into the head of your HTML document ...


```sh
<link rel="stylesheet" href="https://assets.gcloud.fti-group.com/fti-group-icon-font/latest/fti-group-icon-font.css">
```

... or something similar.

📌 **GCS include versioned packages and the latest version of master branch.**


## Development

* checkout/update repository
* add SVG into folder `src`
* commit (incl. short meaningful message)


### How to update GCS

This will happen automatically. You have nothing to do.

### How to update npm

To trigger the publish to npm registry you have to call the following command:

```sh
$ npm version minor
```
 
The build server (travis) will now update the version of the package to the next minor version and publish new npm 
package.


## Misc

### Requirements for development

* git
* github account inlc. membership of tourstream organization
* Node.js >= 8.6.0

### Rules for SVG file names

* file name: kebap-case
* file name: letters only
* file name: limiter -

This file name will be also the class name inside of CSS.

Example: file name `hello-world.svg` and CSS usage `<i class="fg-hello-world"></i>`

***

[npm-version-image]: https://img.shields.io/npm/v/%40tourstream%2Ffti-group-icon-font.svg?style=flat-square
[npm-version-url]: https://www.npmjs.com/package/@tourstream/fti-group-icon-font
[npm-downloads-image]: https://img.shields.io/npm/dm/%40tourstream%2Ffti-group-icon-font.svg?style=flat-square
[npm-downloads-url]: https://www.npmjs.com/package/@tourstream/fti-group-icon-font

[travis-image]: https://img.shields.io/travis/tourstream/fti-group-icon-font.svg?style=flat-square
[travis-url]: https://travis-ci.org/tourstream/fti-group-icon-font

[demo-image]: https://img.shields.io/badge/Demo-latest-%230099cc.svg?style=flat-square
[demo-url]: https://assets.gcloud.fti-group.com/fti-group-icon-font/latest/fti-group-icon-font.html

[license-image]: https://img.shields.io/github/license/tourstream/fti-group-icon-font.svg?style=flat-square
[license-url]: https://github.com/tourstream/fti-group-icon-font/blob/master/LICENSE
