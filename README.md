nicopinto.github.io
===================

## Quick Tools

```javascript
var words = "Si Ernesto se enteró de que ella había vuelto (cómo había vuelto), nunca lo supe, pero el caso es que poco después se fue a vivir a El Tala, y, en todo aquel verano, sólo volvimos a verlo una o dos veces. Costaba trabajo mirarlo de frente. Era como si la idea que Julio nos había metido en la cabeza -porque la idea fue de él, de Julio, y era una idea extraña, turbadora: sucia- nos hiciera sentir culpables. No es que uno fuera puritano, no. A esa edad, y en un sitio como aquél, nadie es puritano. Pero justamente por eso, porque no lo éramos, porque no teníamos nada de puros o piadosos y al fin de cuentas nos parecíamos bastante a casi todo el mundo, es que la idea tenía algo que turbaba. Cierta cosa inconfesable, cruel. Atractiva. Sobre todo, atractiva.".replace(/[,\.\(\)]/g, '').split(' ');

var wordsShuffled = _.shuffle(words);

$('#window').html(wordsShuffled.join(' '));
```
