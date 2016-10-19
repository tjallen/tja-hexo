---
title: react-simple-range
summary: React component
date: 2016-10-12 19:05:50
casestudy: true
thumb: images/reactsimplerange-thumb.jpg
repo: https://github.com/tjallen/react-simple-range
pkg: https://www.npmjs.com/package/react-simple-range
page_links:
- link_text: Slider examples
  link_url: http://www.thomjamesallen.com/projects/react-simple-range-examples
tags:
- JavaScript
- React
- Webpack
---
[![npm version](https://img.shields.io/npm/v/react-simple-range.svg?style=flat)](https://www.npmjs.com/package/react-simple-range)
[![travis build](https://img.shields.io/travis/tjallen/react-simple-range.svg?style=flat)](https://travis-ci.org/tjallen/react-simple-range)
This is a simple React slider component used for inputting a number within a range, a la HTML5 input type="range".

I wanted to get some experience publishing open-source modules and React's focus on composable, reusable components made this a good opportunity.

My aim was to keep it simple and lightweight while progressively adding useful features, largely in the form of optional props that can be passed by the user.

The component was developed in ES6 and transpiled to ES5 by Babel for release as an NPM package. I'm using [semantic-release](https://github.com/semantic-release/semantic-release), [Travis CI](https://travis-ci.org/) and [commitizen](https://github.com/commitizen/cz-cli) for meaningful commit messages, semantic versioning, continuous integration, automated package publishing and releases.

I've included some basic tests with [Mocha](https://mochajs.org/), [Expect](https://github.com/mjackson/expect) and [Enzyme](https://github.com/airbnb/enzyme) but I'm aiming to increase the test coverage when I get time.