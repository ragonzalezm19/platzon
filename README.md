# Platzom

Platzom es un idioma inventado para el [Curso de Fundamentos de Javascript](https://platzi.com/js) de [Platzi](https://platzi.com), el mejor lugar de educación online

## Descripción del idioma

- Si la palabra termina con "ar", se le quitan esas dos letras.
- Si la palabra inicia con Z, se le añade "pe" al final.
- Si la palara traducida tiene 10 o más letras, se debe partir en dos por la mitad y unir con un guión medio
- Por último, si la palabra original es un palindromo, ninguna de las reglas anteriores cuenta y se devuelve la misma palabra pero intercalando letras mayúsculas y menúsculas

## Instalación
```
npm install platzom
```

## Uso

```
import platzom from 'platzom'

platzom("Programar") // Program
platzom("Zorro") // Zorrope
platzom("Zarpar") // Zarppe
platzom("abecedario") // abece-dario
platzom("sometemos") // SoMeTeMoS
```

## Créditos
- [Roberto Gonzalez](https://twitter.com/ragonzalezm19)

## Licencia

[MIT](https://opensource.org/licenses/MIT)