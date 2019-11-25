# Scroll

> An utility for scrolling web pages.

## Usage

Example with [Modal]:

``` javascript
const scroll = new Scroll

modal.map('Command', ['KeyJ'], (event) => scroll.down(event.repeat), 'Scroll down')
modal.map('Command', ['KeyK'], (event) => scroll.up(event.repeat), 'Scroll up')
```

More examples at [Krabby].

## Credits

- [Saka Key] ([@eejdoowad]) for the initial implementation.

## References

- [Create a keyboard interface to the web]

[Krabby]: https://krabby.netlify.com
[Modal]: https://github.com/alexherbo2/modal.js
[Create a keyboard interface to the web]: https://alexherbo2.github.io/blog/chrome/create-a-keyboard-interface-to-the-web/
[Saka Key]: https://key.saka.io
[@eejdoowad]: https://github.com/eejdoowad
