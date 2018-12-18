# Smart property

```
body {
  @include smartp((
    font-size: base,
    background-color: red,
    color: (blue, light),
  ));
}
```

results in:

```
body {
  font-size: 1rem,
  background-color: #f00;
  color: #fff;
}
```

## Voordelen

- Volledige en centrale controle over waardes
- Eigen properties mogelijk

## Hoe werkt het

- ...
