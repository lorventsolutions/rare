# Centered Logo Header

It contains Centered Logo Layout which we can include in any required layouts.

```text
<header class="header">
    <nav class="navbar navbar-static-top">
        <div>
            <a href="index.html" class="logo navbar-brand float-left text-white text-center">
                <!--<h3 class="text-white">Rare Admin</h3>-->
                <img src="img/logo.png" alt="logo" class="img-fluid navbar_brand_img" />
            </a>
            <div class="navbar-btn float-left sidebar-toggle">
                <div>
                    <div class="bar1 first"></div>
                    <div class="bar2 second"></div>
                    <div class="bar3 third"></div>
                </div>
            </div>
            <div class="float-left">
                <div class="menu_search hidden-md-down">
                    <div class="input_icon">
                        <i class="icon_in_input input_icon_left ti-search text-primary"></i>
                        <input type="text" id="menu_filter" autocomplete="off" class="form-control pl-5 br_25" name="search" placeholder="Search...">
                    </div>
                    <!--<input type="search" name="search" class="form-control" >-->
                </div>
            </div>
            <div class="float-left">
                <div class="megamenu">
                    <!--<a class="dropdown mega-dropdown dropdown-content"> </a>-->
                    <a href="#" class="dropdown-toggle text-white"  data-toggle="dropdown">Mega</a>
                    <div class="dropdown-menu mega-dropdown-menu fadein" data-dropdown-in="slideDown" data-dropdown-out="slideUp">
                        <div class="row slide_effect">
                            <div class="col-lg-2 col-sm-6 ">
                                <div class="row p-3">
                                    <div class="col-12">
                                        <h6 class=" heading">Quick Links</h6>
                                    </div>
                                    <div class="col-12">
                                        <ul class="mt-2 mega_links">
                                            <li class="mb-3"><a href="index.html">
                                                <span class="ti-home mr-1 text-primary"></span> Dashbord 1 <span class="ti-angle-right float-right mt-1"></span></a>
                                            </li>
                                            <li class="mb-3"><a href="user_list.html">
                                                <span class="ti-user text-warning mr-1"></span> Users <span class="ti-angle-right float-right mt-1"></span></a>
                                            </li>
                                            <li class="mb-3"><a href="calendar.html">
                                                <span class="ti-calendar text-purple mr-1"></span>Calender<span class="ti-angle-right float-right mt-1"></span></a>
                                            </li>
                                            <li class="mb-3"><a href="widgets1.html">
                                                <span class="ti-palette mr-1 text-danger"></span> Widgets <span class="ti-angle-right float-right mt-1"></span></a>
                                            </li>
                                            <li class="mb-3"><a href="advanced_datatables.html">
                                                <span class="ti-view-grid mr-1 text-success"></span>Tables <span class="ti-angle-right float-right mt-1"></span></a>
                                            </li>
                                            <li class="mb-3"><a href="#">
                                                <span class="ti-paint-bucket mr-1 text-danger"></span>UI Components <span class="ti-angle-right float-right mt-1"></span></a>
                                            </li>
                                            <li class="mb-3"><a href="echart_bar.html">
                                                <span class="ti-pie-chart mr-1 text-primary"></span> Charts <span class="ti-angle-right float-right mt-1"></span></a>
                                            </li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-4 col-sm-6">
                                <div class="row p-3">
                                    <div class="col-12">
                                        <div class="newstick">
                                            <div class="recent">
                                                <div class="row mt-1 recent_row1">
                                                    <div class="col-lg-12 ">
                                                        <div class="media">
                                                            <img src="img/people4.png" class="rounded-circle mr-2" alt="image not found">
                                                            <span class="status-online  m-t-10"></span>
                                                            <div class="media-body">
                                                                <h6 class="mb-1 mt-2">Adam B. Engles <small class="text-success float-right">Online</small></h6>
                                                                <small>Yoga<span class="float-right mt-1">
                               25 / 08 / 2017</span></small>
                                                            </div>

                                                        </div>
                                                    </div>
                                                </div>
                                                <div class="row mt-1 recent_row2">
                                                    <div class="media col-12">
                                                        <img src="img/people5.png" class="rounded-circle mr-2" alt="image not found">
                                                        <span class="status-away  m-t-10"></span>
                                                        <div class="media-body">
                                                            <h6 class="mb-1 mt-2">Barbara A. Egan <small class="float-right text-warning">5mins ago</small></h6>
                                                            <small>Aerobics<span class="float-right mt-1">
                                23 / 08 / 2017</span></small>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div class="row mt-1 recent_row1">
                                                    <div class="media col-12">
                                                        <img src="img/people2.png" class="rounded-circle mr-2" alt="image not found">
                                                        <span class="status-busy  m-t-10"></span>
                                                        <div class="media-body">
                                                            <h6 class="mb-1 mt-8">Caroline G. Turner <small class=" float-right">2 days ago</small></h6>
                                                            <small>Power Yoga<span class="float-right mt-1">
                                 19 / 08 / 2017</span></small>
                                                        </div>
                                                    </div>

                                                </div>
                                                <div class="row mt-1 recent_row2">
                                                    <div class="media col-12">
                                                        <img src="img/people3.png" class="rounded-circle mr-2" alt="image not found">
                                                        <span class="status-online  m-t-10"></span>
                                                        <div class="media-body">
                                                            <h6 class="mb-1 mt-6">Kevin S. McCabe <small class="text-success float-right">Online</small></h6>
                                                            <small>Fitness<span class="float-right mt-1">
                                15 / 08 / 2017</span></small>
                                                        </div>
                                                    </div>

                                                </div>
                                                <div class="row mt-1 recent_row1">
                                                    <div class="media col-12">
                                                        <img src="img/people4.png" class="rounded-circle mr-2" alt="image not found">
                                                        <span class="status-busy  m-t-10"></span>
                                                        <div class="media-body">
                                                            <h6 class="mb-1 mt-2">Richard S. Jensen <small class=" float-right">1 day ago</small></h6>
                                                            <small>Fitness<span class="float-right mt-1">
                                15 / 08 / 2017</span></small>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div class="row mt-1 recent_row2">
                                                    <div class="media col-12">
                                                        <img src="img/people5.png" class="rounded-circle mr-2" alt="image not found">
                                                        <span class="status-away  m-t-10"></span>
                                                        <div class="media-body">
                                                            <h6 class="mb-1 mt-7">Kevin S. McCabe <small class="float-right text-warning">30 mins ago</small></h6>
                                                            <small>Fitness<span class="float-right mt-1">
                                15 / 08 / 2017</span></small>
                                                        </div>
                                                    </div>

                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-3 col-sm-6 ">
                                <div class="row p-3">
                                    <div class="col-12">
                                        <h6 class=" heading">Project Stats</h6>
                                    </div>
                                    <div class="col-12">
                                        <p class="m-0 mt-2">Completed</p>
                                        <div class="progress">
                                            <div class="progress-bar  progress-bar-striped progress-bar-animated bg-success" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 85%"></div>
                                        </div>
                                        <p class="m-t-15 mb-0">Under Process</p>
                                        <div class="progress">
                                            <div class="progress-bar bg-mint progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%"></div>
                                        </div>
                                        <p class="m-t-15 mb-0">Pending Projects</p>
                                        <div class="progress">
                                            <div class="progress-bar bg-danger progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 55%"></div>
                                        </div>
                                        <p class="m-t-15 mb-0">Man Power</p>
                                        <div class="progress">
                                            <div class="progress-bar bg-success progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 90%"></div>
                                        </div>
                                        <p class="m-t-15 mb-0">Client Rating</p>
                                        <div class="progress">
                                            <div class="progress-bar bg-purple progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 80%"></div>
                                        </div>
                                        <p class="m-t-15 mb-0">Under Process</p>
                                        <div class="progress">
                                            <div class="progress-bar bg-info progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 50%"></div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="col-lg-3 col-sm-6">
                                <div class="row p-3">
                                    <div class="col-12">
                                        <!--<h6 class=" heading">Browser Stats</h6>-->
                                    </div>
                                    <div class="col-12 m-t-10">
                                        <!--<iframe  src="https://www.youtube.com/embed/gMaDhkNJA2g"  allowfullscreen></iframe>-->
                                        <img src="img/mobile2.png" class="img-fluid" />
                                    </div>
                                </div>

                            </div>

                        </div>
                    </div>

                </div>
            </div>
            <div>
                <div class="top_right_nav">
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
                    <!--<div class="btn-group hidden-md-up small_device_search float-right" data-toggle="modal" data-target="#search_modal">-->
                    <!--<i class="ti-search text-white"></i>-->
                    <!--</div>-->
                    <!--<div class="top_search_box float-left hidden-sm-down">-->
                    <!--<form class="header_input_search float-right">-->
                    <!--<input class="head_input" type="text" placeholder="Search" name="search">-->
                    <!--<button type="submit">-->
                    <!--<span class="font-icon-search"></span>-->
                    <!--</button>-->
                    <!--<div class="overlay"></div>-->
                    <!--</form>-->
                    <!--</div>-->
                    <!--<div class="modal" id="search_modal" tabindex="-1" role="dialog" >-->
                    <!--<form>-->
                    <!--<div class="modal-dialog" role="document">-->
                    <!--<div class="modal-content">-->
                    <!--<button type="button" class="close" data-dismiss="modal" aria-label="Close">-->
                    <!--<span class="float-right" aria-hidden="true">×</span>-->
                    <!--</button>-->
                    <!--<div class="input-group search_bar_small">-->
                    <!--<input type="text" class="form-control" placeholder="Search..." name="search">-->
                    <!--<span class="input-group-btn">-->
                    <!--<button class="btn btn-secondary" type="submit"><i class="ti-search"></i></button>-->
                    <!--</span>-->
                    <!--</div>-->
                    <!--</div>-->
                    <!--</div>-->
                    <!--</form>-->
                    <!--</div>-->
                </div>
            </div>
        </div>
    </nav>
</header>
```

