---
layout: post
title: Test post
subtitle: [ejemplo]
gh-repo: igomezv
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---

**Here is some bold text**

## Here is a secondary heading

Tabla genérica

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


Figura

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

Figura centrada

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}

Código genérico
~~~

var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```python
print("Hola mundo")
```

And here is the same code yet again but with line numbers:

{% highlight python linenos %}
def saludo(nombre):
	print("Hola {}".format(nombre))
{% endhighlight %}

## Boxes
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
