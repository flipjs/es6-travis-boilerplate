# es6-travis-boilerplate

ES6 - Travis - Nyc - Codecov.io - Ava - Boilerplate

[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg?style=flat-square)](https://github.com/semantic-release/semantic-release)
[![version](https://img.shields.io/npm/v/es6-travis-boilerplate.svg?style=flat-square)](http://npm.im/es6-travis-boilerplate)
[![MIT License](https://img.shields.io/npm/l/es6-travis-boilerplate.svg?style=flat-square)](http://opensource.org/licenses/MIT)
[![travis build](https://img.shields.io/travis/flipjs/es6-travis-boilerplate.svg?style=flat-square)](https://travis-ci.org/flipjs/es6-travis-boilerplate)
[![Codecov](https://img.shields.io/codecov/c/github/flipjs/es6-travis-boilerplate.svg?style=flat-square)](https://codecov.io/github/flipjs/es6-travis-boilerplate)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/feross/standard)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg?style=flat-square)](http://commitizen.github.io/cz-cli/)
[![downloads](https://img.shields.io/npm/dm/es6-travis-boilerplate.svg?style=flat-square)](http://npm-stat.com/charts.html?package=es6-travis-boilerplate&from=2016-03-24)

## How-to

### Set up your github repo

git clone https://github.com/flipjs/es6-travis-boilerplate.git

delete .git directory

git init

edit package.json and rename title

edit keywords in package.json

edit readme and rename title/links

npm install

git add .

run 'npm run commit' for the initial commit

create a new repository at github

git remote add origin https://github.com/your-username/your-repo.git

git push -u origin master

### Set up to publish to NPM (automatically)

run 'semantic-release-cli setup'
- skip creating new .travis.yml as you already have one
- put the `"version": "0.0.0-semantically-released",` back in package.json

start building api and unit testing

run npm run cover && npm run build

git add .

npm run commit

git push

### All done!

The badges on top section of the README should now display some data.

### Additional notes

The dependencies saved to package.json is configured with exact version.
You might need to update it or change it to use semver range operator.

## License

MIT © [Felipe Apostol](https://github.com/flipjs)

