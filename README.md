# [Start Bootstrap - Agency](https://startbootstrap.com/template-overviews/agency/)

[Agency](https://startbootstrap.com/template-overviews/agency/) is a one page agency portfolio theme for [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](http://startbootstrap.com/). This theme features several content sections, a responsive portfolio grid with hover effects, full page portfolio item modals, a responsive timeline, and a working PHP contact form.

## Preview

[![Agency Preview](https://startbootstrap.com/assets/img/templates/agency.jpg)](https://blackrockdigital.github.io/startbootstrap-agency/)

**[View Live Preview](https://blackrockdigital.github.io/startbootstrap-agency/)**

## Status

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/BlackrockDigital/startbootstrap-agency/master/LICENSE)
[![npm version](https://img.shields.io/npm/v/startbootstrap-agency.svg)](https://www.npmjs.com/package/startbootstrap-agency)
[![Build Status](https://travis-ci.org/BlackrockDigital/startbootstrap-agency.svg?branch=master)](https://travis-ci.org/BlackrockDigital/startbootstrap-agency)
[![dependencies Status](https://david-dm.org/BlackrockDigital/startbootstrap-agency/status.svg)](https://david-dm.org/BlackrockDigital/startbootstrap-agency)
[![devDependencies Status](https://david-dm.org/BlackrockDigital/startbootstrap-agency/dev-status.svg)](https://david-dm.org/BlackrockDigital/startbootstrap-agency?type=dev)

## Download and Installation

To begin using this template, choose one of the following options to get started:
* [Download the latest release on Start Bootstrap](https://startbootstrap.com/template-overviews/agency/)
* Install via npm: `npm i startbootstrap-agency`
* Clone the repo: `git clone https://github.com/BlackrockDigital/startbootstrap-agency.git`
* [Fork, Clone, or Download on GitHub](https://github.com/BlackrockDigital/startbootstrap-agency)

## About

Start Bootstrap is an open source library of free Bootstrap templates and themes. All of the free templates and themes on Start Bootstrap are released under the MIT license, which means you can use them for any purpose, even for commercial projects.

* https://startbootstrap.com
* https://twitter.com/SBootstrap

Start Bootstrap was created by and is maintained by **[David Miller](http://davidmiller.io/)**, Owner of [Blackrock Digital](http://blackrockdigital.io/).

* http://davidmiller.io
* https://twitter.com/davidmillerskt
* https://github.com/davidtmiller

Start Bootstrap is based on the [Bootstrap](http://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

Copyright 2013-2018 Blackrock Digital LLC. Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-agency/blob/gh-pages/LICENSE) license.

## Logo

To place a logo image instead of a text you need to do the following:

In the agency.css you have 3 areas where you need to put your logo in different sizes. In my case I used the sizes for the logo of 80px width x 41px height for the smallest, used on mobile phone, 100px x 51px for the shrunk version (when you scroll) and 200px x 102px for the starting screen aka the biggest.

Save your logo on these different sizes and place them in the following areas.

Line 177 in class .navbar-default .navbar-brand , remove the font-family and colour and replace it with the following:

width:80px;
height:41px;
background-image:url(../img/YOUR-Logo-smallest.png);
background-repeat:no-repeat;
margin:5px 0 0 5px; /*better position*/