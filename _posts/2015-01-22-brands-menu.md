---
layout: post
title: brands-menu
description: Snippet para criar um menu de marcas
permalink: brands-menu
---

## brands-menu
Snippet para criar um menu de marcas

{% gist rsantostray/73b3ada27f88de7e4b16 brands_menu.twig %}

## Exemplo
![Menu de Marcas OpenCode]({{ site.baseurl }}/assets/components/brands-menu.png)

## Como usar

Copie o código acima e crie um arquivo separado, ex: elements/snippets/brands_menu.html

Faça a chamada desse arquivo onde desejar: 

{% highlight html+jinja %}
{% raw %}

{{ _view.element('snippets/brands_menu') }}

{% endraw %}
{% endhighlight %}
