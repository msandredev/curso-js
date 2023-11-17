# Aula 03 - A função _console.log()_

É utilizada para mostrar algo na tela.

### Aspas simples X Aspas Duplas X Crase

#### Aspas simples
É permitido inserir _"aspas duplas"_ dentro de aspas simples.

```js
console.log('André "Meira" dos Santos');
```

#### Aspas duplas
É permitido inserir _'aspas simples'_ dentro de aspas duplas.

```js
console.log("André 'Meira' dos Santos");
```

#### Crase
É utilizado para fazer _template streams_, mas é permitido inserir aspas simples e aspas duplas.

```js
console.log(`André 'Meira' dos "Santos"`);
```

### Números
Pode ser inserido números, textos (strings) em uma função `console.log()`.

```js
console.log('Hoje está muito calor e vai fazer', 40, 'graus "Celsius"');
```