_This README is written in portuguese because it searches for synonyms of only portuguese words._

## Sinônimos

Pesquisa por sinônimos de uma palavra em sinonimos.com.br.

```js
const sinonimos = require('node-sinonimos');

sinonimos('fôrma');
// ['modelo', 'matriz', 'recipiente', 'molde', 'caixilho', 'carcaça']

// Se a palavra não for encontrada, ela não existe ou não tem sinônimos,
// então é retornada uma array vazia
sinonimos('abcdef');
// []
```