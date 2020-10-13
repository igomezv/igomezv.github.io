---
layout: post
title: Test post
subtitle: [ejemplo]
gh-repo: igomezv
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---

**Post de prueba**

## Tablas

Tabla genérica

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


### Figuras

![Crepe]("/assets/img/avatar-icon.png")

Figura centrada

![Crepe]("/assets/img/avatar-icon.png"){: .mx-auto.d-block :}

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
LaTeX entre lineas \(\Sigma_{i=0}^n \omega^i\).

Bloque de LaTeX 
</p>

<div class="LATEX">
\begin{equation}
p(\theta | D) \propto p(D | \theta) p(\theta)
\end{equation}

</div>

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
