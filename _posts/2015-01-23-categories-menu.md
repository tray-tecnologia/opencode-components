---
layout: post
title: categories-menu
description: Snippet para criar um menu de categorias
permalink: categories-menu
---

## categories-menu
Snippet para criar um menu de categorias

{% gist rsantostray/73b3ada27f88de7e4b16 categories_menu.html %}

## Exemplo
![Menu de Marcas OpenCode]({{ site.baseurl }}/assets/components/categories-menu.png)

## Como usar

Copie o código acima e crie um arquivo separado, ex: elements/snippets/categories_menu.html

Faça a chamada desse arquivo onde desejar: 

{% highlight html+jinja %}
{% raw %}

{{ _view.element('snippets/categories_menu') }}

{% endraw %}
{% endhighlight %}
