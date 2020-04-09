# Mmenu

It contains mmenu sidebar part which we can include in mmenu layout.

```text
</div>
    <nav id="menu">
        <div class="mmenu_scroll">
            <ul class="listview-icons">
                <li class="{% if (page == 'index1') or (page == 'index2') or (page == 'index3') %} active{% endif %}">
                    <span><i class="menu_icon ti-pencil-alt text-primary"> </i> &nbsp; Dashboard</span>
                    <ul>
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
                        <li  {% if page =='index3'%} class="active" id="active" {% endif %}>
                            <a href="index3.html">
                                <i class="ti-angle-double-right"></i> Dashboard 3
                            </a>
                        </li>
                    </ul>
                </li>

                <li class="{% if (page == 'Widgets1') or (page == 'Widgets2') or (page == 'Widgets3')  %} active{% endif %}">
                    <span><i class="menu_icon ti-palette text-danger"></i> &nbsp; Widgets</span>
                    <ul>
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
                <li class="{% if (page == 'Slider') or (page == 'gridStack') or (page == 'cropper') or (page == 'animations') or (page == 'Timeline1') or (page == 'Timeline2') or (page == 'Transitions') or (page == 'Rating')
                       or (page == 'Notifications') or (page == 'Notifications2') or (page == 'PNotify') or (page == 'Swiper') or (page == 'PricingTable') or (page == 'JStree') %} active{% endif %}">
            <span>
                <i class="menu_icon ti-paint-bucket text-success"></i> &nbsp; UI features
            </span>
                    <ul>
                        <li {% if page =='Slider'%} class="active" id="active" {% endif %}>
                            <a href="sliders.html">
                                <i class="ti-angle-double-right"></i> Sliders
                            </a>
                        </li>
                        <li {% if page =='gridStack'%} class="active" id="active" {% endif %}>
                            <a href="grid_stack.html">
                                <i class="ti-angle-double-right"></i> Grid Stack
                            </a>
                        </li>
                        <li {% if page =='cropper'%} class="active" id="active" {% endif %}>
                            <a href="cropper.html">
                                <i class="ti-angle-double-right"></i> Cropper
                            </a>
                        </li>
                        <li {% if page =='animations'%} class="active" id="active" {% endif %}>
                            <a href="animations.html">
                                <i class="ti-angle-double-right"></i> Animations
                            </a>
                        </li>
                        <li class="{% if (page == 'Timeline1') or (page == 'Timeline2')  %} active{% endif %}">
                    <span>
                        <i class="ti-angle-double-right"></i>&nbsp;Timeline
                    </span>
                            <ul class="sub_menu sub-submenu">
                                <li {% if page =='Timeline1'%} class="active" id="active" {% endif %}>
                                    <a href="timeline1.html">
                                        Timeline 1
                                    </a>
                                </li>
                                <li {% if page =='Timeline2'%} class="active" id="active" {% endif %}>
                                    <a href="timeline2.html">
                                        Timeline 2
                                    </a>
                                </li>
                            </ul>
                        </li>
                        <li {% if page =='Transitions'%} class="active" id="active" {% endif %}>
                            <a href="transitions.html">
                                <i class="ti-angle-double-right"></i> Transitions
                            </a>
                        </li>
                        <li {% if page =='Rating'%} class="active" id="active" {% endif %}>
                            <a href="rating.html">
                                <i class="ti-angle-double-right"></i> Ratings
                            </a>
                        </li>
                        <li class="{% if (page == 'Notifications') or (page == 'Notifications2') or (page == 'PNotify')  %} active{% endif %}">
                    <span>
                        <i class="ti-angle-double-right"></i>&nbsp;Notifications
                    </span>
                            <ul class="sub_menu sub-submenu">
                                <li {% if page =='Notifications'%} class="active" id="active" {% endif %}>
                                    <a href="notifications.html">
                                        Notifications 1
                                    </a>
                                </li>
                                <li {% if page =='Notifications2'%} class="active" id="active" {% endif %}>
                                    <a href="notifications2.html">
                                        Notifications 2
                                    </a>
                                </li>
                                <li {% if page =='PNotify'%} class="active" id="active" {% endif %}>
                                    <a href="p_notify.html">
                                        P-Notify
                                    </a>
                                </li>
                            </ul>
                        </li>
                        <li {% if page =='Swiper'%} class="active" id="active" {% endif %}>
                            <a href="swiper.html">
                                <i class="ti-angle-double-right"></i> Swiper
                            </a>
                        </li>
                        <li {% if page =='PricingTable'%} class="active" id="active" {% endif %}>
                            <a href="pricing_table.html">
                                <i class="ti-angle-double-right"></i> Pricing Tables
                            </a>
                        </li>
                        <li {% if page =='JStree'%} class="active" id="active" {% endif %}>
                            <a href="jstree.html">
                                <i class="ti-angle-double-right"></i>Js tree
                            </a>
                        </li>
                    </ul>
                </li>
                <li class="{% if (page == 'generalComponents') or (page == 'buttons') or (page == 'RadioCheckbox') or (page == 'dateTimePicker')  or (page == 'Modals') or (page == 'alerts') or (page == 'advancedAlerts') or (page == 'SweetAlert')
                      or (page == 'Navbars') or (page == 'fileUpload') or (page == 'GridView') %} active{% endif %}">
             <span>
                <i class="menu_icon ti-world text-warning"></i> &nbsp; Components
            </span>
                    <ul>
                        <li {% if page =='generalComponents'%} class="active" id="active" {% endif %}>
                            <a href="general_components.html">
                                <i class="ti-angle-double-right"></i> General Components
                            </a>
                        </li>
                        <li {% if page =='buttons'%} class="active" id="active" {% endif %}>
                            <a href="buttons.html">
                                <i class="ti-angle-double-right"></i> Buttons
                            </a>
                        </li>
                        <li {% if page =='RadioCheckbox'%} class="active" id="active" {% endif %}>
                            <a href="radio_checkbox.html">
                                <i class="ti-angle-double-right"></i> Radio and Checkboxes
                            </a>
                        </li>
                        <li {% if page =='dateTimePicker'%} class="active" id="active" {% endif %}>
                            <a href="datetime_picker.html">
                                <i class="ti-angle-double-right"></i> Datetime Picker
                            </a>
                        </li>
                        <li {% if page =='Modals'%} class="active" id="active" {% endif %}>
                            <a href="modals.html">
                                <i class="ti-angle-double-right"></i> Modals
                            </a>
                        </li>
                        <li class="{% if (page == 'alerts') or (page == 'advancedAlerts') or (page == 'SweetAlert')  %} active{% endif %}">
                    <span>
                        <i class="ti-angle-double-right"></i> Alerts
                    </span>
                            <ul class="sub_menu sub-submenu">
                                <li {% if page =='alerts'%} class="active" id="active" {% endif %}>
                                    <a href="alerts.html">
                                        Alerts
                                    </a>
                                </li>
                                <li {% if page =='advancedAlerts'%} class="active" id="active" {% endif %}>
                                    <a href="advanced_alerts.html">
                                        Advanced Alerts
                                    </a>
                                </li>
                                <li {% if page =='SweetAlert'%} class="active" id="active" {% endif %}>
                                    <a href="sweetalerts.html">
                                        Sweet Alerts
                                    </a>
                                </li>
                            </ul>
                        </li>

                        <li {% if page =='Navbars'%} class="active" id="active" {% endif %}>
                            <a href="navbars.html">
                                <i class="ti-angle-double-right"></i> Navbars
                            </a>
                        </li>
                        <li {% if page =='fileUpload'%} class="active" id="active" {% endif %}>
                            <a href="file_upload.html">
                                <i class="ti-angle-double-right"></i> File Uploads
                            </a>
                        </li>
                        <li {% if page =='GridView'%} class="active" id="active" {% endif %}>
                            <a href="grid_view.html">
                                <i class="ti-angle-double-right"></i> Grid View
                            </a>
                        </li>

                    </ul>
                </li>
                <li class="{% if (page == 'cards') or (page == 'advancedCards') or (page == 'draggableCards')  %} active{% endif %}">
             <span>
                <i class="ti-layers-alt menu_icon text-info"></i> &nbsp; Cards
            </span>
                    <ul>
                        <li {% if page =='cards'%} class="active" id="active" {% endif %}>
                            <a href="cards.html">
                                <i class="ti-angle-double-right"></i> Basic Cards
                            </a>
                        </li>
                        <li {% if page =='advancedCards'%} class="active" id="active" {% endif %}>
                            <a href="advanced_cards.html">
                                <i class="ti-angle-double-right"></i> Advanced Cards
                            </a>
                        </li>
                        <li {% if page =='draggableCards'%} class="active" id="active" {% endif %}>
                            <a href="draggable_cards.html">
                                <i class="ti-angle-double-right"></i>  Draggable Cards
                            </a>
                        </li>
                    </ul>
                </li>
                <li class="{% if (page == 'basicFormElements') or (page == 'advancedFormElements') or (page == 'AdvancedFormElements2') or (page == 'Summernote') or (page == 'Tinymce')
                      or (page == 'formlayouts') or (page == 'formWizards') or (page == 'formValidation') %} active{% endif %}">
             <span>
                <i class="menu_icon ti-pencil-alt text-danger"></i> &nbsp; Forms
            </span>
                    <ul>
                        <li class="{% if (page == 'basicFormElements') or (page == 'advancedFormElements') or (page == 'AdvancedFormElements2')  %} active{% endif %}">
                    <span>
                        <i class="ti-angle-double-right"></i> Form Elements
                    </span>
                            <ul class="sub_menu sub-submenu">
                                <li {% if page =='basicFormElements'%} class="active" id="active" {% endif %}>
                                    <a href="basic_form_elements.html">
                                        Basic Form Elements
                                    </a>
                                </li>
                                <li {% if page =='advancedFormElements'%} class="active" id="active" {% endif %}>
                                    <a href="advanced_form_elements.html">
                                        Advanced Form Elements 1
                                    </a>
                                </li>
                                <li {% if page =='AdvancedFormElements2'%} class="active" id="active" {% endif %}>
                                    <a href="advanced_form_elements2.html">
                                        Advanced Form Elements 2
                                    </a>
                                </li>
                            </ul>
                        </li>
                        <li class="{% if (page == 'Summernote') or (page == 'Tinymce')  %} active{% endif %}">
                    <span>
                        <i class="ti-angle-double-right"></i> Form Editors
                    </span>
                            <ul class="sub_menu sub-submenu">
                                <li {% if page =='Summernote'%} class="active" id="active" {% endif %}>
                                    <a href="summernote.html">Summernote</a>
                                </li>
                                <li {% if page =='Tinymce'%} class="active" id="active" {% endif %}>
                                    <a href="tinymce.html">Tinymce</a>
                                </li>

                            </ul>
                        </li>
                        <li {% if page =='formlayouts'%} class="active" id="active" {% endif %}>
                            <a href="form_layouts.html">
                                <i class="ti-angle-double-right"></i> Form Layouts
                            </a>
                        </li>

                        <li {% if page =='formWizards'%} class="active" id="active" {% endif %}>
                            <a href="form_wizards.html">
                                <i class="ti-angle-double-right"></i> Form Wizards
                            </a>
                        </li>
                        <li {% if page =='formValidation'%} class="active" id="active" {% endif %}>
                            <a href="form_validation.html">
                                <i class="ti-angle-double-right"></i> Form Validations
                            </a>
                        </li>
                    </ul>
                </li>
                <li {% if page =='calendar'%} class="active" id="active" {% endif %}>
                    <a href="calendar.html">
                        <span><i class="menu_icon ti-calendar text-warning"></i>&nbsp; Calendar</span>
                    </a>
                </li>
                <li class="{% if (page == 'ThemifyIcons') or (page == 'fontawesomeIcons') or (page == 'IonIcons') or (page == 'LineIcons') or (page == 'VaadinIcons') %} active{% endif %}">
             <span>
                <i class="menu_icon ti-package text-purple"></i> &nbsp; Icons
            </span>
                    <ul>
                        <li {% if page =='ThemifyIcons'%} class="active" id="active" {% endif %}>
                            <a href="themify_icons.html">
                                <i class="ti-angle-double-right"></i> Themify Icons
                            </a>
                        </li>
                        <li {% if page =='fontawesomeIcons'%} class="active" id="active" {% endif %}>
                            <a href="fontawesome_icons.html">
                                <i class="ti-angle-double-right"></i> Fontawesome Icons
                            </a>
                        </li>

                        <li {% if page =='IonIcons'%} class="active" id="active" {% endif %}>
                            <a href="ion_icons.html">
                                <i class="ti-angle-double-right"></i> Ion Icons
                            </a>
                        </li>
                        <li {% if page =='LineIcons'%} class="active" id="active" {% endif %}>
                            <a href="simple_line_icons.html">
                                <i class="ti-angle-double-right"></i> Simple Line Icons
                            </a>
                        </li>
                        <li {% if page =='VaadinIcons'%} class="active" id="active" {% endif %}>
                            <a href="vaadin_icons.html">
                                <i class="ti-angle-double-right"></i> Vaadin Icons
                            </a>
                        </li>
                    </ul>
                </li>
                <li {% if page =='colorPalette'%} class="active" id="active" {% endif %}>
                    <a href="color_palette.html">
                        <i class="menu_icon ti-brush text-mint"></i> &nbsp; Color Palette
                    </a>
                </li>
                <li {% if page =='Typography'%} class="active" id="active" {% endif %}>
                    <a href="typography.html">
                        <i class="menu_icon ti-smallcap text-primary"></i> &nbsp; Typography
                    </a>
                </li>
                <li class="{% if (page == 'Inbox') or (page == 'SentMail') or (page == 'emailView') or (page == 'compose') or (page == 'drafts') or (page == 'Trash') or (page == 'allMails') %} %}  active{% endif %}">
            <span>
                <i class="menu_icon ti-email text-danger"></i> &nbsp; Emails
            </span>
                    <ul>
                        <li {% if page =='Inbox'%} class="active" id="active" {% endif %}>
                            <a href="inbox.html">
                                <i class="ti-angle-double-right"></i> Inbox
                            </a>
                        </li>
                        <li {% if page =='SentMail'%} class="active" id="active" {% endif %}>
                            <a href="sent_mail.html">
                                <i class="ti-angle-double-right"></i> Sent Mail
                            </a>
                        </li>

                        <li {% if page =='emailView'%} class="active" id="active" {% endif %}>
                            <a href="email_view.html">
                                <i class="ti-angle-double-right"></i> View Mail
                            </a>
                        </li>
                        <li {% if page =='compose'%} class="active" id="active" {% endif %}>
                            <a href="compose.html">
                                <i class="ti-angle-double-right"></i> Compose
                            </a>
                        </li>
                        <li {% if page =='drafts'%} class="active" id="active" {% endif %}>
                            <a href="drafts.html">
                                <i class="ti-angle-double-right"></i> Drafts
                            </a>
                        </li>
                        <li {% if page =='Trash'%} class="active" id="active" {% endif %}>
                            <a href="trash.html">
                                <i class="ti-angle-double-right"></i> Trash
                            </a>
                        </li>
                        <li {% if page =='allMails'%} class="active" id="active" {% endif %}>
                            <a href="all_mails.html">
                                <i class="ti-angle-double-right"></i> All Mails
                            </a>
                        </li>
                    </ul>
                </li>
                <li class="{% if (page == 'Profile1') or (page == 'Profile2') or (page == 'UserList') or (page == 'addUser') or (page == 'deleteuser')%}  active{% endif %}">
             <span>
                <i class="menu_icon ti-user text-success"></i> &nbsp; Users
            </span>
                    <ul>
                        <li {% if page =='Profile1'%} class="active" id="active" {% endif %}>
                            <a href="profile1.html">
                                <i class="ti-angle-double-right"></i> User Profile 1
                            </a>
                        </li>
                        <li {% if page =='Profile2'%} class="active" id="active" {% endif %}>
                            <a href="profile2.html">
                                <i class="ti-angle-double-right"></i> User Profile 2
                            </a>
                        </li>
                        <li {% if page =='UserList'%} class="active" id="active" {% endif %}>
                            <a href="user_list.html">
                                <i class="ti-angle-double-right"></i> User List
                            </a>
                        </li>
                        <li {% if page =='addUser'%} class="active" id="active" {% endif %}>
                            <a href="add_user.html">
                                <i class="ti-angle-double-right"></i> Add User
                            </a>
                        </li>

                        <li {% if page =='deleteuser'%} class="active" id="active" {% endif %}>
                            <a href="delete_user.html">
                                <i class="ti-angle-double-right"></i> Delete User
                            </a>
                        </li>
                    </ul>
                </li>
                <li class="{% if (page == 'SimpleTables') or (page == 'fooTables') %}  active{% endif %}">
            <span>
                <i class="menu_icon ti-view-grid text-purple"></i> &nbsp; Tables
            </span>
                    <ul>
                        <li {% if page =='SimpleTables'%} class="active" id="active" {% endif %}>
                            <a href="simple_tables.html">
                                <i class="ti-angle-double-right"></i> Simple tables
                            </a>
                        </li>
                        <li {% if page =='fooTables'%} class="active" id="active" {% endif %}>
                            <a href="foo_tables.html">
                                <i class="ti-angle-double-right"></i> Foo Tables
                            </a>
                        </li>
                    </ul>
                </li>
                <li class="{% if (page == 'SimpleDatatables') or (page == 'datatables') or (page == 'advancedDatatables') %}  active{% endif %}">
             <span>
                <i class="menu_icon ti-server text-warning"></i> &nbsp; Data Tables
            </span>
                    <ul>
                        <li {% if page =='SimpleDatatables'%} class="active" id="active" {% endif %}>
                            <a href="simple_datatables.html">
                                <i class="ti-angle-double-right"></i> Simple Datatables
                            </a>
                        </li>
                        <li {% if page =='datatables'%} class="active" id="active" {% endif %}>
                            <a href="datatables.html">
                                <i class="ti-angle-double-right"></i>  Datatables
                            </a>
                        </li>
                        <li {% if page =='advancedDatatables'%} class="active" id="active" {% endif %}>
                            <a href="advanced_datatables.html">
                                <i class="ti-angle-double-right"></i>  Advanced Datatables
                            </a>
                        </li>
                    </ul>
                </li>
                <li class="{% if (page == 'lineEcharts') or (page == 'barEcharts') or (page == 'pieEcharts') %}  active{% endif %}">
            <span>
                <i class="menu_icon ti-pie-chart text-primary"></i> &nbsp; E charts
            </span>
                    <ul>
                        <li {% if page =='lineEcharts'%} class="active" id="active" {% endif %}>
                            <a href="echart_line.html">
                                <i class="ti-angle-double-right"></i> Line Echarts
                            </a>
                        </li>
                        <li {% if page =='barEcharts'%} class="active" id="active" {% endif %}>
                            <a href="echart_bar.html">
                                <i class="ti-angle-double-right"></i>  Bar Echarts
                            </a>
                        </li>
                        <li {% if page =='pieEcharts'%} class="active" id="active" {% endif %}>
                            <a href="echart_pie.html">
                                <i class="ti-angle-double-right"></i>  Pie Ecahrts
                            </a>
                        </li>
                    </ul>
                </li>
                <li {% if page =='MorrisCharts'%} class="active" id="active" {% endif %}>
                    <a href="morris_chart.html">
                        <i class="menu_icon ti-pulse text-purple"></i> &nbsp;
                        <span>Morris Charts</span>
                    </a>
                </li>
                <li {% if page =='SparklineChart'%} class="active" id="active" {% endif %}>
                    <a href="sparkline_charts.html">
                        <i class="menu_icon ti-stats-down text-mint"></i> &nbsp;
                        <span>Sparkline Charts</span>
                    </a>
                </li>
                <li class="{% if (page == 'LineChartist') or (page == 'barChartist') or (page == 'PieChartist') %}  active{% endif %}">
            <span>
                <i class="menu_icon ti-bar-chart text-danger"></i> &nbsp; Chartist
            </span>
                    <ul>
                        <li {% if page =='LineChartist'%} class="active" id="active" {% endif %}>
                            <a href="line_chartist.html">
                                <i class="ti-angle-double-right"></i> Line Chartist
                            </a>
                        </li>
                        <li {% if page =='barChartist'%} class="active" id="active" {% endif %}>
                            <a href="bar_chartist.html">
                                <i class="ti-angle-double-right"></i> Bar Chartist
                            </a>
                        </li>
                        <li {% if page =='PieChartist'%} class="active" id="active" {% endif %}>
                            <a href="pie_chartist.html">
                                <i class="ti-angle-double-right"></i> Pie Chartist
                            </a>
                        </li>
                    </ul>
                </li>
                <li class="{% if (page == 'c3LineChart') or (page == 'c3BarChart') %}  active{% endif %}">
             <span>
                <i class="menu_icon ti-bar-chart-alt text-info"></i> &nbsp; C3 Charts
            </span>
                    <ul>
                        <li {% if page =='c3LineChart'%} class="active" id="active" {% endif %}>
                            <a href="c3_line_chart.html">
                                <i class="ti-angle-double-right"></i> C3 Line Charts
                            </a>
                        </li>
                        <li {% if page =='c3BarChart'%} class="active" id="active" {% endif %}>
                            <a href="c3_bar_chart.html">
                                <i class="ti-angle-double-right"></i>  C3 Bar Charts
                            </a>
                        </li>
                    </ul>
                </li>
                <li {% if page =='NDV3Charts'%} class="active" id="active" {% endif %}>
                    <a href="nvd3_charts.html">
                        <i class="menu_icon ti-stats-up text-warning"></i>
                        <span>NVD3 Charts</span>
                    </a>
                </li>
                <li {% if page =='Rickshaw'%} class="active" id="active" {% endif %}>
                    <a href="rickshaw.html">
                        <i class="menu_icon ti-power-off text-primary"></i>
                        <span>Rickshaw</span>
                    </a>
                </li>
                <li {% if page =='PerityCharts'%} class="active" id="active" {% endif %}>
                    <a href="peity_charts.html">
                        <i class="menu_icon ti-bolt text-purple"></i>
                        <span>Peity Charts</span>
                    </a>
                </li>
                <li class="{% if (page == 'flotLineCharts') or (page == 'flotBarCharts') or (page == 'flotPieCharts') %}  active{% endif %}">
             <span>
                <i class="menu_icon ti-pulse text-danger"></i> &nbsp; Flot Charts
            </span>
                    <ul>
                        <li {% if page =='flotLineCharts'%} class="active" id="active" {% endif %}>
                            <a href="flot_line_charts.html">
                                <i class="ti-angle-double-right"></i> Flot Line Charts
                            </a>
                        </li>
                        <li {% if page =='flotBarCharts'%} class="active" id="active" {% endif %}>
                            <a href="flot_bar_charts.html">
                                <i class="ti-angle-double-right"></i> Flot Bar Charts
                            </a>
                        </li>
                        <li {% if page =='flotPieCharts'%} class="active" id="active" {% endif %}>
                            <a href="flot_pie_charts.html">
                                <i class="ti-angle-double-right"></i> Flot Pie Charts
                            </a>
                        </li>
                    </ul>
                </li>
                <li class="{% if (page == 'LineAmcharts') or (page == 'columnBarAmcharts') or (page == 'PieFunnelAmcharts') or (page == 'gaugeAmcharts') %}  active{% endif %}">
             <span>
                <i class="menu_icon ti-pie-chart text-warning"></i> &nbsp; Amcharts
            </span>
                    <ul>
                        <li {% if page =='LineAmcharts'%} class="active" id="active" {% endif %}>
                            <a href="line_amcharts.html">
                                <i class="ti-angle-double-right"></i> Line Amcharts
                            </a>
                        </li>
                        <li {% if page =='columnBarAmcharts'%} class="active" id="active" {% endif %}>
                            <a href="column_bar_amcharts.html">
                                <i class="ti-angle-double-right"></i> Bar Amcharts
                            </a>
                        </li>
                        <li {% if page =='PieFunnelAmcharts'%} class="active" id="active" {% endif %}>
                            <a href="pie_funnel_amcharts.html">
                                <i class="ti-angle-double-right"></i> Pie Funnel Amcharts
                            </a>
                        </li>
                        <li {% if page =='gaugeAmcharts'%} class="active" id="active" {% endif %}>
                            <a href="gauge_amcharts.html">
                                <i class="ti-angle-double-right"></i> Gauge Amcharts
                            </a>
                        </li>
                    </ul>
                </li>
                <li {% if page =='chartJs'%} class="active" id="active" {% endif %}>
                    <a href="chartjs.html">
                        <i class="menu_icon ti-stats-down text-success"></i> &nbsp;
                        <span>Chartjs</span>
                    </a>
                </li>
                <li class="{% if (page == 'basicGmaps') or (page == 'gmapServices') or (page == 'gmapRoutes') or (page == 'gmapUtils') or (page == 'vectormaps') %}  active{% endif %}">
            <span>
                <i class="menu_icon ti-pie-chart text-warning"></i> &nbsp; Maps
            </span>
                    <ul>
                        <li class="{% if (page == 'basicGmaps') or (page == 'gmapServices') or (page == 'gmapRoutes') or (page == 'gmapUtils')  %}  active{% endif %}">
                    <span>
                        <i class="ti-angle-double-right"></i> Gmaps
                    </span>
                            <ul>
                                <li {% if page =='basicGmaps'%} class="active" id="active" {% endif %}>
                                    <a href="gmaps_basic.html">
                                        Basic Gmaps
                                    </a>
                                </li>
                                <li {% if page =='gmapServices'%} class="active" id="active" {% endif %}>
                                    <a href="gmaps_services.html">
                                        Gmap Services
                                    </a>
                                </li>
                                <li {% if page =='gmapRoutes'%} class="active" id="active" {% endif %}>
                                    <a href="gmap_routes.html">
                                        Gmap Routes
                                    </a>
                                </li>
                                <li {% if page =='gmapUtils'%} class="active" id="active" {% endif %}>
                                    <a href="gmap_utils.html">
                                        Gmap Utils
                                    </a>
                                </li>
                            </ul>
                        </li>
                        <li {% if page =='vectormaps'%} class="active" id="active" {% endif %}>
                            <a href="vectormaps.html">
                                <i class="ti-angle-double-right"></i> Vector Maps &nbsp;
                            </a>
                        </li>
                    </ul>
                </li>
                <li class="{% if (page == 'gallery') or (page == 'VideoGallery') or (page == 'flippingGallery') or (page == 'fancygallery') %}  active{% endif %}">
            <span>
                <i class="menu_icon ti-gallery text-purple"></i> &nbsp; Galleries
            </span>
                    <ul>
                        <li {% if page =='gallery'%} class="active" id="active" {% endif %}>
                            <a href="gallery1.html" class="dropdown_head">
                                <i class="ti-angle-double-right"></i> Gallery
                            </a>
                        </li>
                        <li {% if page =='VideoGallery'%} class="active" id="active" {% endif %}>
                            <a href="video_gallery.html" class="dropdown_head">
                                <i class="ti-angle-double-right"></i> Video Gallery
                            </a>
                        </li>
                        <li {% if page =='flippingGallery'%} class="active" id="active" {% endif %}>
                            <a href="gallery3.html" class="dropdown_head">
                                <i class="ti-angle-double-right"></i> Flipping Gallery
                            </a>
                        </li>
                        <li {% if page =='fancygallery'%} class="active" id="active" {% endif %}>
                            <a href="gallery4.html" class="dropdown_head">
                                <i class="ti-angle-double-right"></i> Fancy Gallery
                            </a>
                        </li>
                    </ul>
                </li>
                <li {% if page =='blank'%} class="active" id="active" {% endif %}>
                    <a href="blank.html">
                        <i class="menu_icon ti-file text-info"></i> Blank
                    </a>
                </li>
                <li>
                    <a href="login.html">
                        <i class="menu_icon ti-shift-right text-success"></i> Login
                    </a>
                </li>
                <li>
                    <a href="register.html">
                        <i class="menu_icon ti-marker-alt text-warning"></i> Register
                    </a>
                </li>
                <li class="{% if  page == 'Invoice' %}  active{% endif %}">
            <span>
                <i class="menu_icon ti-files text-danger"></i> &nbsp; Extra Pages
            </span>
                    <ul>
                        <li>
                            <a href="404.html">
                                <i class="ti-angle-double-right"></i>  404
                            </a>
                        </li>
                        <li>
                            <a href="500.html">
                                <i class="ti-angle-double-right"></i> 500
                            </a>
                        </li>
                        <li>
                            <a href="forgot_password.html">
                                <i class="ti-angle-double-right"></i> Forgot Password
                            </a>
                        </li>
                        <li>
                            <a href="lockscreen.html">
                                <i class="ti-angle-double-right"></i> Lockscreen
                            </a>
                        </li>
                        <li {% if page =='Invoice'%} class="active" id="active" {% endif %}>
                            <a href="invoice.html">
                                <i class="ti-angle-double-right"></i> Invoice
                            </a>
                        </li>
                    </ul>
                </li>
                <li>
             <span>
                <i class="menu_icon ti-view-list text-info"></i> &nbsp; Menu levels
            </span>
                    <ul>
                        <li>
                            <a href="javascript:void(0)">
                                <i class="ti-angle-double-right"></i> Level 1
                            </a>
                        </li>
                        <li>
                    <span>
                        <i class="ti-angle-double-right"></i> Level 1
                    </span>
                            <ul class="sub_menu sub-submenu">
                                <li>
                                    <a href="#">
                                        Level 2
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        Level 2
                                    </a>
                                </li>
                                <li>
                                    <a href="#">
                                        Level 2
                                    </a>
                                </li>
                            </ul>
                        </li>
                    </ul>
                </li>
            </ul>
        </div>
    </nav>
```

