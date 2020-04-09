# Layouts

Using this macro file we can call particular layout from all the layouts by using command `gulp nunjucks --layout layoutname`.

```text
{% macro layout_type(layout) %}

{% if layout=="default" %}
    {% extends "default.html" %}

{% elif layout=="fixed-menu" %}
    {% extends "fixed-menu.html" %}

{% elif layout=="fixed-header" %}
    {% extends "fixed-header.html" %}

{% elif layout=="compact-menu" %}
    {% extends "compact-menu.html" %}

{% elif layout=="centered-logo" %}
    {% extends "centered-logo.html" %}

{% elif layout=="horizontal-layout" %}
    {% extends "horizontal-layout.html" %}

{% elif layout=="dark-layout" %}
    {% extends "dark-layout.html" %}

{% elif layout=="icon-horizontal" %}
    {% extends "icon-horizontal.html" %}

{% elif layout=="fullwidth-layout" %}
    {% extends "fullwidth-layout.html" %}

{% elif layout=="fixed-footer" %}
    {% extends "fixed-footer.html" %}

{% elif layout=="header-style1" %}
    {% extends "header-style1.html" %}

{% elif layout=="light-sidebar" %}
{% extends "light-sidebar.html" %}

{% elif layout=="mmenu" %}
{% extends "mmenu.html" %}

{% else %}

    {% extends "default.html" %}


{% endif %}
{% endmacro %}

{{ layout_type(layout) }}
```

