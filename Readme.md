*This repository is a mirror of the [component](http://component.io) module [component/css](http://github.com/component/css). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-css`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# css

  jQuery's [css()](http://api.jquery.com/css/) method.

## Installation

  Install with [component(1)](http://component.io):

    $ component install component/css

## API

### css(el, prop)

Get the computed value of the `prop` on `el`.

```js
css(p, 'color')
```

### css(el, prop, value)

Set the CSS `value` on the `prop` on `el`

```js
css(p, 'color', 'red')
```

### css(el, styles)

Set a `styles` object to `el`

```js
css(p, {
  color: 'red',
  background: 'blue'
})
```

## TODO

- Finish porting jQuery [css unit tests](https://github.com/jquery/jquery/blob/master/test/unit/css.js) over

## License

  MIT
