### HTML

The various card HTML variations of previous versions are now replaced by two simple examples. One with the default footer and one with a footer designed to display icon buttons and an app's status.

### SCSS

The `_card.scss` file is now located at __src/components/card/card.scss__. You will need to update any `@import` statements for this file to reflect this change.

```scss
@import 'path_to_node_modules/@console/bluemix-components/src/components/card/card';
```

`.bx--card__card-footer` is now `.bx--card-footer`


### JavaScript

`cardKeyPress()` is now a private method renamed `_cardKeyPress()`.
