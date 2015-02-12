---
layout: post
title: smart-filter
description: Snippet para criar um filtro inteligente
permalink: smart-filter
---

## smart-filter
Snippet para criar um filtro inteligente

{% gist rsantostray/73b3ada27f88de7e4b16 smart_filter.twig %}

## Exemplo
![Menu de Marcas OpenCode]({{ site.baseurl }}/assets/components/smart-filter.png)

## Como usar

Copie o código acima e crie um arquivo separado, ex: elements/snippets/smart_filter.html

Faça a chamada desse arquivo onde desejar: 

{% highlight html+jinja %}
{% raw %}

{{ _view.element('snippets/smart_filter') }}

{% endraw %}
{% endhighlight %}
