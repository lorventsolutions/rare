# Breadcrumb 1

It contains breadcrumb style part which we can include in breadcrumb macro file.

```text
<div class="content-header container-fluid bg-white">
    <div class="row">
        <div class="col-sm-4">
            <h4 class="pb-1"><i class="{{ bc_icon }}"></i> {{ title }}</h4>
        </div>
        <div class="col-sm-8">
            <ol class="breadcrumb float-right">
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
    </div>

</div>
```

