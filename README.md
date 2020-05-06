# sass-responsive-pack

A simple lib to work with responsive projects using SASS

This lib is very easy to use.

If you want to build any responsive project use it and you'll see how is simple and easy make responsive behaviors.

## How it's works

I created some mixins with names to make it easier for you to remember.

Before, you need import the mixin file in sass file that you will work:

```scss
@import "../../../../assets/scss/mixins/responsive";
```

and now you can use them.

For example, if you need some behavior in desktop screens, you just need:

```scss
.card {
  @import min-desktop-size {
    // your style
  }
}
```

Or, if you need work with large desktop screens:

```scss
.card {
  @import min-desktop-large-size {
    // your style
  }
}
```

In cases you need use up to tablet size, you just:

```scss
.card {
  @import max-tablet-size {
    // your style
  }
}
```
