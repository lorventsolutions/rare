# Header

It contains default header style part which we can include in any required layouts.

```text
<div class="preloader">
    <div class="preloader_img">
        <img src="img/loader.gif" class="pre_img" alt="loading...">
    </div>
</div>
<header class="header">
    <nav class="navbar navbar-static-top">
        <div>
            <a href="index2.html" class="logo navbar-brand float-left text-white text-center">
                <img src="img/logo.png" alt="logo" class="img-fluid navbar_brand_img"/>
            </a>
            <div class="navbar-btn float-left sidebar-toggle">
                <div>
                    <div class="bar1 first"></div>
                    <div class="bar2 second"></div>
                    <div class="bar3 third"></div>
                </div>
            </div>
            <div class="top_right_nav">
                <div class="float-left">
                    <div class="menu_search hidden-md-down mt-1">
                        <div class="input_icon">
                            <i class="icon_in_input input_icon_left ti-search text-primary"></i>
                            <input type="text" id="menu_filter" autocomplete="off" class="form-control pl-5 br_25" name="search" placeholder="Search...">
                        </div>
                        <!--<input type="search" name="search" class="form-control" >-->
                    </div>
                </div>
                <div class="float-right">
                    <!--start admin setting section-->
                    <div class="dropdown">
                        <a id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            <img src="img/admin.jpg" class="admin_img2 img-fluid rounded-circle avatar-img" alt="avatar">

                        </a>
                        {% include "./user_details.html" %}
                    </div>
                    <!--end admin setting section-->
                </div>
                <div class="messages float-right">
                    <!--start admin setting section-->
                    <div class="dropdown">
                        <a data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            <i class="ti-email text-white"></i>
                            <div class="messages_badge_top">
                                <span class="badge badge-warning">3</span>
                            </div>
                        </a>
                        {% include "./messages.html" %}
                    </div>
                    <!--end admin setting section-->
                </div>
                <div class="notifications float-right">
                    <!--start admin setting section-->
                    <div class="dropdown">
                        <a data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            <i class="ti-bell text-white"></i>
                            <div class="notifications_badge_top">
                                <span class="badge badge-danger">4</span>
                            </div>
                        </a>
                        {% include "./notifications.html" %}
                    </div>
                    <!--end admin setting section-->
                </div>
                <div class="fullscreen float-right hidden-xs-down">
                    <i class="ti-fullscreen text-white full_screen"></i>
                </div>
            </div>
        </div>
    </nav>
</header>
```

