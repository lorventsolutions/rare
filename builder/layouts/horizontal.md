# Horizontal

The design for the blank page in Horizontal Layout by run the command `gulp nunjucks --layout horizontal-layout --breadcrumb * --color *` through builder is shown below:

And you can change breadcrumb and color for header in this layout by run the command `gulp nunjucks --layout default --beadcrumb * --color *`

Where `--beadcrumb *`is

`--breadcrumb (default,0,1,2,3,4,5)`

Where `--color *`is

`--color (default,primary,success,danger,mint,purple)`

![](../../.gitbook/assets/rare72.png)

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
    <link rel="stylesheet" href="vendors/slimmenu/css/slimmenu.min.css">
    <link type="text/css" rel="stylesheet" href="css/pages/horizontal.css">
    {% block header_styles %}{% endblock %}
    <!--End page level styles-->
</head>
<body>
<!--Start header-->
{% include "partials/header.html" %}
<!--End header-->
<!--Start horizontal layout-->
{% include "partials/horizontal_layout.html" %}
<!--End horizontal layout-->
<!--Start wraper-->
<div class="wrapper">
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
<script src="vendors/slimmenu/js/jquery.slimmenu.min.js" type="text/javascript"></script>
<script type="text/javascript" src="js/pages/horizontal.js"></script>
{% block footer_scripts %}{% endblock %}
End page level scripts
</body>
</html>
```

