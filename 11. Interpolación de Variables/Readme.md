# Interpolación de Variables

Escribir 4 reglas en Sass que generen declaraciones en CSS utilizando los ejemplos de interpolación de variables debajo


```
$lados: ['right','left'];

@each $lado in $lados{
    .col-#{$lado} {
      border-#{$lado}: 1px solid #ccc;
      padding-#{$lado}: 1rem;
    }
}
```

```
$icons: (
  checkmark: "\e600",
  plus:      "\e601",
  minus:     "\e602"
);

@each $name, $value in $icons {
  .icon-#{$name} {
    &:before { content: $value; padding:5px }
  }
}

```