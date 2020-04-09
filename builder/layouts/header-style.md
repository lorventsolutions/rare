# Header Style

The design for the blank page in Header Style Layout by run the command `gulp nunjucks --layout header-style1 --breadcrumb * --color *` through builder is shown below:

And you can change breadcrumb and color for header in this layout by run the command `gulp nunjucks --layout default --beadcrumb * --color *`

Where `--beadcrumb *`is

`--breadcrumb (default,0,1,2,3,4,5)`

Where `--color *`is

`--color (default,primary,success,danger,mint,purple)`

![](../../.gitbook/assets/rare77.png)

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
    <link type="text/css" rel="stylesheet" href="css/pages/nav_style.css" />
    <!--End page level styles-->
</head>

<body>
<!--Start styled header-->
{% include "partials/header.html" %}
<!--End styled header-->
<!--Start wrapper-->
<div class="wrapper">
    <!--Start leftmenu-->
    {% include "partials/leftmenu.html" %}
    <!--End leftmenu-->
    <div class="right-aside view-port-height">
        <!--Start breadcrumb-->
        {% include "macros/breadcrumb.html" %}
        <!--End breadcrumb-->
        {% block content %}{% endblock %}
        <!--Start block content-->
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

