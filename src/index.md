---
title: JSON bases
layout: base
---
Object: {"key": "value"}  
Array: ["value1", "value2"]

- A key is always a string
- A value can be: string, number, object, array, true/false, null

## This is two objects
{{object.firstObject}}  
{{object.secondObject}}

## This is an array
{% for i in array %}
- {{i}}
{%- endfor %}