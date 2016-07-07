# JavaScript Proxy

> :goat: For learning how to use [JavaScript Proxy](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Proxy), or just to see what is possible through metaprogramming in modern JavaScript. Tries to collect resources such as presentations, articles, modules and examples using Proxy, Reflect and other intercession type metaprogramming.

> The Proxy object was included in the ES2015 iteration of the standard and is available in all evergreen browsers and Node.js v6. Unfortunately as it is a big language semantic change, it cannot be polyfilled through transpilers such as Babel.

Know of any brilliant resources? [Let us know](https://github.com/mikaelbr/proxy-fun/issues/new) and we'll create a vast collection of awesomeness.

## Resources

### Presentations

- Slides: [Metaprogramming SUPERPOWERS](http://slides.com/elektronik/metaprogramming-via-es2015-proxies#/) by Nickolay Ribal
- Video: [Breaking the Fourth Wall With JavaScript](https://opbeat.com/events/web-rebels-2016/#breaking-the-fourth-wall-with-javascript) by Mikael Brevik

### Articles
- [Exploring JS chapter 28. Metaprogramming with proxies](http://exploringjs.com/es6/ch_proxies.html) by Dr. Axel Rauschmayer
- [ES6 Proxies in Depth](https://ponyfoo.com/articles/es6-proxies-in-depth) by Nicolás Bevacqua
- [Introducing ES2015 Proxies](https://developers.google.com/web/updates/2016/02/es2015-proxies?hl=en) by Addy Osmani
- [ES6 In Depth: Proxies](https://hacks.mozilla.org/2015/07/es6-in-depth-proxies-and-reflect/) by Jason Orendorff

### Modules/Packages

- [zer](https://github.com/jbmusso/zer): Zer helps you serialize any JavaScript chains to String representations of any languages by leveraging ES2015 `Proxy` objects
- [negative-array](https://github.com/sindresorhus/negative-array): Negative array index support `array[-1]` using ES2015 Proxy

---

## Examples in this repo

Run all examples in this repo by using `node@6`:

```shell
$ node ./examples/<example-file>.js
```

Examples using tracing and tests can be run using `npm`:

```shell
$ npm test
```

Remember to install all example dependencies by doing `npm i`
