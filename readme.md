# Animate.scss
> A SCSS port of daneden's [animate.css](https://github.com/daneden/animate.css) that doesn't suck.

## Why another one?
This will add the used animations automagically. No need for a settings file or import
specific animations.

## Usage
```scss
@import 'animate';

.element {
  @include animate('fadeIn', '1s ease-in 2s');
}
```

## License
MIT
