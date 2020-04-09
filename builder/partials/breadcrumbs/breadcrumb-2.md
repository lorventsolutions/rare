# Breadcrumb 2

It contains breadcrumb style part which we can include in breadcrumb macro file.

```text
<div class="content-header container-fluid bg-white">
    <div class="row">
        <div class="col-sm-12">
            <ol class="breadcrumb pb-0">
                <li class="breadcrumb-item">
                    <a href="#">Home</a>
                </li>
                {% for item in breadcrumb %}
                <li class="breadcrumb-item">
                    <a href="#">{{item.name}}</a>
                </li>
                {% endfor %}
            </ol>
        </div>
        <div class="col-sm-12">
            <h4 class="mt-0 pt-0 pb-1">{{ title }}</h4>
        </div>

    </div>
</div>
```

