# simple-media-queries

## Sublime Snippets

Copy and paste these snippets to your Sublime Snippets folder. You can access it by opening Sublime > Preferences > Browse Packages > User.

I suggest making a new folder for these snippets (e.g. css).

### Snippet Shortcuts

Press `mu` + `TAB` for

```
@media #{$mobile-up} {
  
}
```

Press `tu` + `TAB` for

```
@media #{$tablet-up} {
  
}
```

Press `sdu` + `TAB` for

```
@media #{$sdesktop-up} {
  
}
```

Press `du` + `TAB` for

```
@media #{$desktop-up} {
  
}
```

Press `lu` + `TAB` for

```
@media #{$large-up} {
  
}
```

Press `xlu` + `TAB` for

```
@media #{$xlarge-up} {
  
}
```

## Media Query Variables

These are very simple media query variables that I always use. Simply include them in your project's SCSS folder. These work with the sublime snippets I created above.

    $mobile-cutoff: 480px;
    $tablet-cutoff: 768px;
    $sdesktop-cutoff: 992px;
    $desktop-cutoff: 1200px;
    $large-cutoff: 1600px;
    $xlarge-cutoff: 1920px;

    $mobile-down: "only screen and (max-width: #{$mobile-cutoff})";
    $tablet-down: "only screen and (max-width: #{$tablet-cutoff})";
    $sdesktop-down: "only screen and (max-width: #{$sdesktop-cutoff})";
    $desktop-down: "only screen and (max-width: #{$desktop-cutoff})";
    $large-down: "only screen and (max-width: #{$large-cutoff})";
    $xlarge-down: "only screen and (max-width: #{$xlarge-cutoff})";

    $mobile-up: "only screen and (min-width: #{$mobile-cutoff})";
    $tablet-up: "only screen and (min-width: #{$tablet-cutoff})";
    $sdesktop-up: "only screen and (min-width: #{$sdesktop-cutoff})";
    $desktop-up: "only screen and (min-width: #{$desktop-cutoff})";
    $large-up: "only screen and (min-width: #{$large-cutoff})";
    $xlarge-up: "only screen and (min-width: #{$xlarge-cutoff})";

    $retina-up: "(-webkit-min-device-pixel-ratio: 2) and (min-width: 1281px), (min-resolution: 192dpi) and (min-width: 1281px)";


