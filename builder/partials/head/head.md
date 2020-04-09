# Head

It contains Default head part which we can include in any layout.It included with header colors .By using gulp you can change header colors also.

```text
    {% if color=="default" %}
    {% set skin = 'css/skins/default_skin.css' %}
    {% elif color=="primary" %}
    {% set skin = 'css/skins/primary_skin.css' %}
    {% elif color=="success" %}
    {% set skin = 'css/skins/success_skin.css' %}
    {% elif color=="danger" %}
    {% set skin = 'css/skins/danger_skin.css' %}
    {% elif color=="mint" %}
    {% set skin = 'css/skins/mint_skin.css' %}
    {% elif color=="purple" %}
    {% set skin = 'css/skins/purple_skin.css' %}
    {% else %}
    {% set skin = 'css/skins/default_skin.css' %}
    {% endif %}
    <meta charset="UTF-8">
    <meta content='width=device-width, initial-scale=1, maximum-scale=1' name='viewport'>
    <link rel="shortcut icon" href="img/logo2.ico"/>
    <!--start global css-->
    <link type="text/css" rel="stylesheet" href="css/app.css" />
    <!-- end of global css -->
    <link type="text/css" rel="stylesheet" href="css/custom.css" />
    <link type="text/css" rel="stylesheet" href="{{skin}}"/>
```

