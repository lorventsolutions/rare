# Setting Layout As Default

When you run the command `gulp`, you will get the view in default layout style set earlier. If you would like other layouts, each time you need to run the command like `gulp nunjucks --layout name`

To simplify the above work, replace a part of the code of `layout.html` \(available in path `src/templates/macros/layout.html)`

as follows.

**Existing code in layout.html**

```text
{% macro layout_type(layout) %}

{% if layout=="default" %}
    {% extends "default.html" %}

{% elif layout=="fixed-footer" %}
    {% extends "fixed-footer.html" %}

<!--our code-->

    {% else %}
    {% extends "default.html" %}

{% endif %}
{% endmacro %}

{{ layout_type(layout) }}
```

Replacing code:

In the above code replace the code

```text
{% else %}
{% extends "default.html" %}
```

with

```text
{% else %}
 {% extends "horizontal-layout.html" %}
```

When the above code is replaced, it is not necessary to run like `gulp nunjucks --layout name` each time. Just simply run `gulp`.

That is all what you need to do.

