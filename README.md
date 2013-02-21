# SCSS Corner Ribbon

## HTML
```
<div><span class="label">NEW</span></div>
```

## SCSS
```
@import "mixins";
@import "corner_ribbon";

div {
  @include corner-ribbon(#507ea4);
}
```

## Arguments
 1. `$color` (default: red)
 2. `$box_size` (default: 85px)
 3. `$side_drop_width` (default: 6px)

## License
[Public Domain](http://unlicense.org/)