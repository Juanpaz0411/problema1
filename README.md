# Angulo de desviacion minimo en patron de difracción de una rendija
##### *Juan José Paz Hormiga*
## problema
calcular el angulo en el que se localiza la interferencia constructiva o destructiva 'm' de dos fuentes puntuales.

## Teoria.

la interferencia de dos ondas existe o no dependiendo si se cumplen las siguientes condiciones:

Las dos ondas son monocromaticas, igualmente polarizadas y coerentes entre si.

Si estas dos condiciones se cumplen es posible estudiar el patron que interferencia que dejan en detectores o pantallas tal y como se muestra a continuacion


<p align="center">
  <img src="https://github.com/Juanpaz0411/problema-I/blob/main/imagenes/WhatsApp%20Image%202023-09-13%20at%206.31.57%20PM.jpeg" alt="portada" width="350" />
  <br>
</p>

Es posible calcular caracteristicas de este fenomeno tales como la longitud de onda, angulos de interferencia minimos y maximos, intensidad de la señal, entre otros.

El angulo en el que estan determinados los maximos de interferencia es calculado por:

d sen(θ) = m λ

El angulo en el que estan los minimos es calculado por 

d sen(θ) = (m+0.5) λ

Usando metodos numericos es posible encontrar los angulos a los que se encuentran los ordenes minimos y maximos de difracción.

## Metodo de la bisección.
evaluando en:

d sen(θ) - m λ = 0 para maximos 

d sen(θ) - (m+0.5) λ = 0 para minimos

## Metodo de Newton-Raphson.
derivando respecto a θ:

f'(θ) = d cos(θ)

## Metodo de la falsa posición.
θ = θ<sub>b</sub> + <sup>f(θ<sub>b</sub>)(θ<sub>a</sub>-θ<sub>b</sub>)  </sup>/<sub>f(θ<sub>b</sub>)-f(θ<sub>a</sub>)</sub>
