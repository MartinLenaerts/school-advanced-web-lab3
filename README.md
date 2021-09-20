# TP3 


## Réponses aux questions :
# 

### <u>  Question 1 </u>
### That is the main difference between local installation and global installation of packages with npm? What kind of packages do you generally install locally? What kind is generally installed globally?
<br> 

```
Installer des packages localement permet d'installler des packages seulement dans le projet en cours. A l'inverse, l'installation global, installe les packages sur l'ordinateur.

Les packages utilisés régulierement seront installéen global. Et les packages spécifiques au projet en cours seront installés en local.
```

### <u> Question 2 </u>
### Webpack is internally used by the Vue CLI. Why is it required to deal with both multiple JavaScript files and special extensions like .vue?

```

```
<br> 

### <u> Question 3 </u>
### What is the role of babel and how browserslist may configure its output?

```
babel est un transcompilateur, il permet de compiler le js pouvant ensuite être intéprété par des navigateurs plus anciens.

Le paramètre 'browserslist' permet de filtrer les navigateurs compatibles ( > 1% , not dead ...)
```
<br> 

### <u> Question 4 </u>
### What is eslint and which set of rules are currently applied? The eslint configuration may be defined in a eslint.config.js or in package.json depending on the setup.

```
Les règles appliquées à eslint sont :
{
    root : true,
    env : {
        node :true
    }
}

Ces règles définissent l'environnement dans lequel le js est executé et si le dossier courant est le dossier parent
```
<br> 

### <u> Question 5 </u>
### What is the difference between scoped and non-scoped CSS?

```
Le css scoped est appliqué seulement au composant courant, à l'inverse du css non-scoped qui lui est appliqué à tous les éléments de la page
```
<br> 

### <u> Question 6 </u>
### How behaves non-prop attributes (aka. HTML attributes) passed down to a component, when its template has a single root element? Tips: it is well documented by vue, but you can also try it youself by passing the style attribute with a straight visual effect.

```

```
<br> 


### <u> Question 7 </u>
### Analyse how works the AsyncButton. When is the parent @click event called? How the child component is aware of the returned Promise by the parent onClick handler? Why is the await necessary? Etc.

```

```
<br> 


### <u> Question 8 </u>
### Which bug is introduced if inheritAttrs: false is missing or set to true in AsyncButton. Why?

```

```





