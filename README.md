# ejs2pug

S� criando a ideia ainda, levantando as convers�es que dever�o ser feitas, listando as Compara��es.
A princ�pio ser� feito alguns regex para fazer replace da syntax.

## Uso

### convert

```console
> ejs2pug convert lista-produtos.ejs
```

## Compara��es pug com ejs

A seguir recursos do pug e comparando-os com ejs.

### include

ejs

```javascript
include('includes/head.ejs')
```

pug [includes](https://pugjs.org/language/includes.html)

```pug
include includes/head.pug
```

## Compara��es pug com ejs

A seguir recursos do ejs e comparando-os com pug.

## for of

ejs

```javascript
for (produto of produtos) {
	// algo
}
```

pug [iteration](https://pugjs.org/language/iteration.html)

```pug
each produto in produtos
	//- algo
```