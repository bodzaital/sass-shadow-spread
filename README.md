# How to use

Import the mixin file:

```scss
@import "mixin_spread";
```

Include the shadow mixin where you want to use it:

```scss
.example-text-shadow
{
    @include text-shadow(0, 0, .5rem, 3, rgb(0, 0, 0));
}

.example-block-shadow
{
    @include box-shadow(0, 0, .5rem, 3, rgb(0, 0, 0));
}
```
