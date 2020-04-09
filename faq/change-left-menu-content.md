# Change Left Menu Content

If you want to change the content in left menu you need to edit following file and recompile.

File path:-`src/templates/partials/leftmenu.html`

```text
<!-- Left side column. contains the logo and sidebar -->
    <div class="left_aside">
        <!-- sidebar: style can be found in sidebar-->
        <div class="sidebar">
            <!--user profile section-->
            <div class="user_section">
                <div class="row">
                    <div class="col-5">
                        <img src="img/admin.jpg" alt="user not found" class="rounded-circle">
                    </div>
                    <div class="col-7">
                        <p class="text-white mt-2 mb-0">John Doe</p>
                        <div class="leftuser_icons">
                            <span class="float-left"><a href="profile2.html">
                            <i class="ti-user text-white"></i></a></span><span class="float-left">
                            <a href="inbox.html"><i class="ti-email text-white"></i></a></span>
                            <span class="float-left"><a href="lockscreen.html">
                            <i class="ti-lock text-white"></i></a></span>
                        </div>
                    </div>
                </div>
            </div>
            <div id="menu" role="navigation">
                <ul class="navigation">
                    <li class="menu-dropdown {% if (page == 'index1') or (page == 'index2') %} active
                    {% endif %}">
                        <a href="#" class="dropdown_head">
                            <i class="menu_icon ti-home text-primary"></i>
                            <span class="mm-text ">Dashboard</span>
                            <span class="ti-angle-up"></span>
                        </a>
                        <ul class="sub_menu">
                            <li {% if page =='index1'%} class="active" id="active" {% endif %}>
                                <a href="index.html">
                                    <i class="ti-angle-double-right"></i> Dashboard 1
                                </a>
                            </li>
                            <li  {% if page =='index2'%} class="active" id="active" {% endif %}>
                                <a href="index2.html">
                                    <i class="ti-angle-double-right"></i> Dashboard 2
                                </a>
                            </li>
                        </ul>
                    </li>
                    <li class="menu-dropdown {% if (page == 'Widgets1') or (page == 'Widgets2') or
                     (page == 'Widgets3')  %} active{% endif %}">
                        <a href="#" class="dropdown_head">
                            <i class="menu_icon ti-palette text-danger"></i>
                            <span class="mm-text "> Widgets</span>
                            <span class="ti-angle-up"></span>
                        </a>
                        <ul class="sub_menu">
                            <li {% if page =='Widgets1'%} class="active" id="active" {% endif %}>
                                <a href="widgets1.html">
                                    <i class="ti-angle-double-right"></i> Widgets 1
                                </a>
                            </li>
                            <li {% if page =='Widgets2'%} class="active" id="active" {% endif %}>
                                <a href="widgets2.html">
                                    <i class="ti-angle-double-right"></i> Widgets 2
                                </a>
                            </li>
                            <li {% if page =='Widgets3'%} class="active" id="active" {% endif %}>
                                <a href="widgets3.html">
                                    <i class="ti-angle-double-right"></i> Widgets 3
                                </a>
                            </li>
                        </ul>
                    </li>
                </ul>
                <!-- / .navigation -->
            </div>
            <!-- menu -->
        </div>
        <!-- /.sidebar -->
    </div>
```

