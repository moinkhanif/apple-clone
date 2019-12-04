# Apple Clone

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

Recreating the archived 2014 version of [apple.com](https://web.archive.org/web/20140301004610/http://www.apple.com/) website

## About the project

![Apple 2014 picture](https://i.imgur.com/FRpxDAm.png)

We were to recreate an older version of apple website from scratch. The following is my version of the website

![Apple Clone](https://i.imgur.com/yYecE01.png)

## Features

* My version uses texts instead of picture positioning trick as texts are easier to render

* In an attempt to use pure css and html for this project, I decided to go for "focus" pseudo class and add the background property, instead of expanding the whole search bar.

```sh
input#search:focus,
input#search:focus ~ i {
  background: #fff;
  color: black;
}
```

* I used flex and margin auto to position elements as it was more convenient.
* I also used various icons from FontAwesome website.

<!-- MARKDOWN LINKS & IMAGES -->

[contributors-shield]: https://img.shields.io/github/contributors/moinkhanif/apple-clone.svg?style=flat-square
[contributors-url]: https://github.com/moinkhanif/apple-clone/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/moinkhanif/apple-clone.svg?style=flat-square
[forks-url]: https://github.com/moinkhanif/apple-clone/network/members
[stars-shield]: https://img.shields.io/github/stars/moinkhanif/apple-clone.svg?style=flat-square
[stars-url]: https://github.com/moinkhanif/apple-clone/stargazers
[issues-shield]: https://img.shields.io/github/issues/moinkhanif/apple-clone.svg?style=flat-square
[issues-url]: https://github.com/moinkhanif/apple-clone/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/moinkhanif
[product-screenshot]: images/screenshot.png
