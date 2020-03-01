# scroll.js

scroll.js is a JavaScript library for scrolling web pages.

Scrolls web pages smoothly.  Works around the quirks of [keydown] events.

[keydown]: https://developer.mozilla.org/en-US/docs/Web/API/Document/keydown_event

A live demo can be found in [Krabby].

[Krabby]: https://krabby.netlify.com

## Installation

Add [`scroll.js`](src/scroll.js) to your project.

## Usage

Example with [modal.js]:

[modal.js]: https://github.com/alexherbo2/modal.js

``` javascript
const scroll = new Scroll

modal.map('Command', ['KeyJ'], ({ repeat }) => scroll.down(repeat), 'Scroll down', 'Scroll')
modal.map('Command', ['KeyK'], ({ repeat }) => scroll.up(repeat), 'Scroll up', 'Scroll')
```

You can find some examples in [Krabby].

See the [source](src/scroll.js) for a complete reference.

## Credits

- [Saka Key] ([@eejdoowad]) for the initial implementation.
- [@AdamWagner] for his work in [#1] to unify scrolling mechanisms.

[#1]: https://github.com/alexherbo2/scroll.js/issues/1

[Saka Key]: https://key.saka.io

[@eejdoowad]: https://github.com/eejdoowad
[@AdamWagner]: https://github.com/AdamWagner
