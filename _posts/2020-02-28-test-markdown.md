---
layout: post
title: Test post
subtitle: [ejemplo]
gh-repo: igomezv
gh-badge: [star, fork, follow]
tags: [test]
comments: true
useMath: true
---

**Post de prueba**

## Tablas

Tabla genérica

| A | B | C |
| :------ |:--- | :--- |
| No | Nombre | Ciudad |
| 1 | Eleven | México |
| 2 | Eight | Veracruz |



### Figuras

![Ícono](https://igomezv.github.io/assets/img/avatar-icon.png)

Figura centrada

![Figura](https://igomezv.github.io/assets/img/avatar-icon.png){: .mx-auto.d-block :}

### Código

Código genérico
~~~

var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

Código en python:

```python
print("Hola mundo")
```

Código numerado:

{% highlight python linenos %}
def saludo(nombre):
	print("Hola {}".format(nombre))
{% endhighlight %}


<p>
Ejemplo de <code>código entre </code> texto.
</p>

<p>
Probando ecuaciones

\begin{equation}
	\Sigma_{i=0}^n w_i x_i
\end{equation}

$x^2 + y^2$

[Link de prueba](http://example.com)


```

### Cajas
Cajas de notificaciones, advertencias y de errores.

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
