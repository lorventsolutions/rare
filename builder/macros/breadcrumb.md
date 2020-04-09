# Breadcrumb

Using this macro file we can call particular breadcrumb from all the breadcrumbs by using `gulp nunjucks --layout layoutname --breadcumb breadcrumbname.` Breadcrumb Names are `bc-default, 1, 2, 3, 4, 5` and `0`.

```text
{% macro page_bc(bc) %}

{% if bc=="default" %}
    {% include "partials/bc-default.html" %}

{% elif bc=="0" %}


{% elif bc=="1" %}
    {% include "partials/bc1.html" %}

{% elif bc=="2" %}
    {% include "partials/bc2.html" %}

{% elif bc=="3" %}
    {% include "partials/bc3.html" %}

{% elif bc=="4" %}
    {% include "partials/bc4.html" %}

{% elif bc=="5" %}
    {% include "partials/bc5.html" %}

{% else %}
    {% include "partials/bc-default.html" %}
{% endif %}
{% endmacro %}

{{ page_bc(bc) }}
```

