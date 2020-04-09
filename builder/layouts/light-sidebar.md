# Light Sidebar

The design for the blank page in Light sidebar Layout by run the command `gulp nunjucks --layout light-sidebar --breadcrumb * --color *` through builder is shown below:

And you can change breadcrumb and color for header in this layout by run the command `gulp nunjucks --layout default --beadcrumb * --color *`

Where `--beadcrumb *`is

`--breadcrumb (default,0,1,2,3,4,5)`

Where `--color *`is

`--color (default,primary,success,danger,mint,purple)`

![](../../.gitbook/assets/light_sidebar.png)

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
    <link type="text/css" rel="stylesheet" href="css/pages/light_sidebar.css" />
    <!--End page level styles-->
</head>
<body>
<!--Start header-->
{% include "partials/header.html" %}
<!--End header-->
<!--Start breadcrumb-->
{% include "macros/breadcrumb.html" %}
<!--End breadcrumb-->
<!--Start wrapper-->
<div class="wrapper">
    <!--Start leftmenu-->
    {% include "partials/leftmenu.html" %}
    <!--End leftmenu-->
    <div class="right-aside view-port-height">
        <!--Start block content-->
    {% block content %}{% endblock %}
        <!--End block content-->
    </div>
</div>
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

