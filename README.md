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
```

# Syntax

```
text-shadow(offset-x, offset-y, blur-radius, blur-count, color);
```

where

```
<offset-x> = <length>
<offset-y> = <length>
<blur-radius> = <length>
<blur-count> = <number>
<color> = <color>
```
