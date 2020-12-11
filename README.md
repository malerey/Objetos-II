# Objetos II

1)

Recorrer el siguiente objeto, y por cada propiedad mostrar en consola el mensaje `La propiedad ${propiedad} vale ${valor}`

```js
const producto = {
  id: 'ADA-020',
  title: 'Gubergren sed est amet voluptua',
  price: 123.75,
  picture: 'https://i.kinja-img.com/gawker-media/image/upload/s--53mPze4a--/c_scale,f_auto,fl_progressive,q_80,w_800/1315358249455433031.jpg',
  condition: 'nuevo',
  free_shipping: true,
  location: 'Capital Federal'
};
```

Recuerden utilizar la notacion de corchetes

2)

Crear la funcion hasProperty que recibe dos parametros: un objeto y un string. Si el string es una propiedad dentro del objeto, la funcion retorna true. Si no, retorna false. 

Podes chequear tu codigo con los siguientes ejemplos:


```js
const user = {
  username: 'ada_lovelace',
  password: '1234567890!'
};

const user2 = {
  username: 'grace_hopper',
  password: '1234567890!',
  email: 'grace@hopper.com'
};

console.log( hasProperty(user, 'email') ); // false
console.log( hasProperty(user, 'password') ); // true
console.log( hasProperty(user, 'id') ); // false

console.log( hasProperty(user2, 'email') ); // true
console.log( hasProperty(user2, 'password') ); // true
console.log( hasProperty(user2, 'id') ); // false
```

