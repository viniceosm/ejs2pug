# ejs2pug

Só criando a ideia ainda, levantando as conversões que deverão ser feitas, listando as Comparações.
A princípio será feito alguns regex para fazer replace da syntax.

## Uso

### convert

```console
> ejs2pug convert lista-produtos.ejs
```

## Comparações pug com ejs

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

## Comparações pug com ejs

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