# StewRL

1. 这是StewRL中文技术手册

## site.pages

<!-- prettier-ignore-start -->

| source          | link                                                           |
| --------------- | -------------------------------------------------------------- |
{% for page in site.pages -%}
| {{ page.path }} | [{{ page.url | relative_url }}]({{ page.url | relative_url }}) |
{% endfor %}

<!-- prettier-ignore-end -->


## Local debug

```sh
make
make server
```

## The license

