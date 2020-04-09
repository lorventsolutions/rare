# Breadcrumb 4

It contains breadcrumb style part which we can include in breadcrumb macro file.

```text
<div class="content-header container-fluid bg-white breadcrumb_search">
    <div class="row">
        <div class="col-12">
            <h4 class="d-inline-block">{{ title }}</h4>
            <ol class="breadcrumb d-inline-block">
                <li class="breadcrumb-item">
                    <a href="#">Home</a>
                </li>
                {% for item in breadcrumb %}
                <li class="breadcrumb-item">
                    <a href="#">{{item.name}}</a>
                </li>
                {% endfor %}
            </ol>
            <div class="float-right m-t-10 mb-3">
                <div class="menu_search mt-1">
                    <div class="input_icon">
                        <i class="icon_in_input input_icon_left ti-search text-primary"></i>
                        <input type="text" autocomplete="off" class="form-control pl-5 br_25 menu_filter" name="search" placeholder="Search...">
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
```

