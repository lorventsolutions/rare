# Default

The design for the blank page in Default Layout by run the command `gulp nunjucks --layout default` through builder is shown below:

And you can change breadcrumb and color for header in this layout by run the command `gulp nunjucks --layout default --beadcrumb * --color *`

Where `--beadcrumb *`is

`--breadcrumb (default,0,1,2,3,4,5)`

Where `--color *`is

`--color (default,primary,success,danger,mint,purple)`

![](../../.gitbook/assets/rare52.png)

It has the following Structure:

```text
<!DOCTYPE html>
<html lang="en">
<head>
    <title>{{title}} | Rare admin</title>
    <!--Start common styles-->
    {% include "partials/head.html" %}
    <!--End common styles-->
    <!--Start page level styles-->
    {% block header_styles %}{% endblock %}
    <!--End page level styles-->
</head>
<body>
<!--Start heaader-->
{% include "partials/header.html" %}
<!--End header-->
<!--Start  wrapper-->
<div class="wrapper">
    <!--Start left menu-->
    {% include "partials/leftmenu.html" %}
    <!--End left menu-->
    <div class="right-aside view-port-height">
        <!--Start breadcrumb-->
        {% include "macros/breadcrumb.html" %}
        <!--End breadcrumb-->
        <!--Start block content-->
        {% block content %}{% endblock %}
        <!--End block content-->
    </div>
</div>
<!--End wrapper-->
<!--Start footer-->
{% include "partials/footer.html" %}
<!--End footer-->
<!--Start common scripts-->
{% include "partials/end.html" %}
<!--End common scripts-->
<!--Start page level scripts-->
{% block footer_scripts %}{% endblock %}
<!--End page level scripts-->
</body>
</html>
```

