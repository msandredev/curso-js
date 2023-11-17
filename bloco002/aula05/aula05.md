# Aula 05 - Executando o código via NodeJS e Code Runner

#### Executando via terminal

```js
node index.js
```

#### Criando e executando um index.html no navegador

No VS Code, para criar um arquivo com um template pronto em HTML basta:

- Criar arquivo com extensão **_.html_**
- Ao abrir o arquivo, pressionar o caractere de exclamação (!). O VS Code vai sugerir duas opções, selecione a que tem apenas uma exclamação e pressione enter.

Outra opção é: 
    
- Digitar **_html:5_**

Exemplo de arquivo HTML:

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Minha primeira página HTML</title>
</head>
<body>
    
    <script src="./js/index.js"></script>
</body>
</html>
```

##### #BOAS PRÁTICAS
- É altamente recomendável que o arquivo HTML não tenha o código fonte Javascript, mas sim um link para o arquivo com extensão '.js'

- No arquivo HTML, pode-se incluir a chamada ao arquivo javascript (index.js) tanto na tag \<head\> quanto na tag \<body\>.


> OBS: Inserir o link para o código JS na tag <head> não é uma boa prática pois pode retardar o carregamento da página. O melhor a se fazer é incluir no final da tag _\<body\>_ pois assim será feito o carregamento da página HTML primeiro (renderização) e somente depois carregará o script do JS.