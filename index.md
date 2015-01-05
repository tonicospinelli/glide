---
layout: default
permalink: /
title: Introduction
---

# Introduction

[![Author](http://img.shields.io/badge/author-@reinink-blue.svg?style=flat-square)](https://twitter.com/reinink)
[![Source Code](http://img.shields.io/badge/source-thephpleague/glide-blue.svg?style=flat-square)](https://github.com/thephpleague/glide)
[![Latest Version](https://img.shields.io/github/release/thephpleague/glide.svg?style=flat-square)](https://github.com/thephpleague/glide/releases)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)<br />
[![Build Status](https://img.shields.io/travis/thephpleague/glide/master.svg?style=flat-square)](https://travis-ci.org/thephpleague/glide)
[![Coverage Status](https://img.shields.io/scrutinizer/coverage/g/thephpleague/glide.svg?style=flat-square)](https://scrutinizer-ci.com/g/thephpleague/glide/code-structure)
[![Quality Score](https://img.shields.io/scrutinizer/g/thephpleague/glide.svg?style=flat-square)](https://scrutinizer-ci.com/g/thephpleague/glide)
[![Total Downloads](https://img.shields.io/packagist/dt/league/glide.svg?style=flat-square)](https://packagist.org/packages/league/glide)

Glide is a wonderfully easy on-demand image manipulation library written in PHP. It's straightforward API is exposed via HTTP, similar to cloud image processing services like [Imgix](http://www.imgix.com/) and [Cloudinary](http://cloudinary.com/). Glide leverages powerful libraries like [Intervention Image](http://image.intervention.io/) (image handling and manipulation) and [Flysystem](http://flysystem.thephpleague.com/) (file system abstraction). Glide was created by [Jonathan Reinink](https://twitter.com/reinink).

[![© Photo Joel Reynolds](https://glide.herokuapp.com/kayaks.jpg?w=1000&gam=.9&sharp=8)](https://glide.herokuapp.com/kayaks.jpg?w=1000&gam=.9&sharp=8)

© Photo [Joel Reynolds](http://www.joelreynolds.ca/)

## Highlights

- Adjust, resize and add effects to images using a simple HTTP based API.
- Manipulated images are automatically cached and served with far-future expires headers.
- Create your own image processing server or integrate Glide directly into your app.
- Supports both the [GD](http://php.net/manual/en/book.image.php) library and the [Imagick](http://php.net/manual/en/book.imagick.php) PHP extension.
- Ability to secure image URLs using a private signing key.
- Works with many different file systems, thanks to the [Flysystem](http://flysystem.thephpleague.com/) library.
- Powered by the battle tested [Intervention Image](http://image.intervention.io/) image handling and manipulation library.