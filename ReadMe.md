# test

Ejemplo simple en R para practicar el uso de GitHub.

## Descripción

El script [01_test.R](01_test.R) evalúa una función arbitraria `y = f(x)` con parámetros fijos y grafica el resultado con `ggplot2`.

La función es una onda sinusoidal amortiguada:

```
y = a * sin(b * x) * exp(-c * x) + d
```

| Parámetro | Valor | Descripción                   |
|-----------|-------|-------------------------------|
| `a`       | 2.0   | Amplitud                      |
| `b`       | 0.5   | Frecuencia                    |
| `c`       | 0.1   | Tasa de decaimiento exponencial |
| `d`       | 1.0   | Desplazamiento vertical       |

Los valores de `x` van de 0 a 20 con paso 0.1. El gráfico muestra la curva en azul y una línea horizontal discontinua en `y = d`.

## Requisitos

- R
- Paquete `ggplot2`:

```r
install.packages("ggplot2")
```

## Uso

```r
source("01_test.R")
```

## Cambios propuestos

1. Usar `xMin` y `xMax` para crear `x`.
2. Cambiar las etiquetas de los ejes x e y.
3. Cambiar el color y el tipo de línea del gráfico.
4. Agregar una leyenda (caption) a la figura.

## Participantes

Cata, Rui y Katherine

Contacto: Nico
