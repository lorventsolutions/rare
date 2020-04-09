# Change Breadcrumb

When you run the command `gulp`, you will get the view in default breadcrumb style set earlier. If you would like other breadcrumbs, each time you need to run the command like `gulp nunjucks --breadcrumb name`

To simplify the above work replace a part of the code of `breadcrumb.html` \(available in path `src/templates/macros/breadcrumb.html) as follows.`

**Existing code in breadcrumb.html**

```text
{% macro page_bc(bc) %}

{% if bc=="default" %}
    {% include "partials/bc-default.html" %}

{% elif bc=="0" %}

{% elif bc=="2" %}
    {% include "partials/bc2.html" %}

    <!-- Our code -->

{% else %}
    {% include "partials/bc-default.html" %}

{% endif %}
{% endmacro %}

{{ page_bc(bc) }}
```

Replacing code:

In the above code replace the code

```text
{% else %}
    {% include "partials/bc-default.html" %}
```

with

```text
{% else %}
    {% include "partials/bc1.html" %}
```

When the above code is replaced, it is not necessary to run like `gulp nunjucks --breadcrumb name` each time. Just simply run `gulp`.

That is all what you have to do

