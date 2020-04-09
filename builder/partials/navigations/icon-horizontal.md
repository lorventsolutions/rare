# Icon Horizontal

It contains Icon Horizontal menu part which we can include in Icon Horizontal layout.

```text
<div class="horizontal_menu icon_hr_menu">
    <div class="container-fluid">
        <div class="row">
            <div class="col-md-12">
                <ul id="navigation" class="slimmenu">
                    <li class="main-menu">
                        <a href="javascript:void(0)" class="menu-list text-center {% if (page == 'index1') or (page == 'index2') or (page == 'index3') %} active{% endif %}">
                            <p><span class="ti-home font_18 text-primary"> </span></p> Dashboard
                        </a>
                        <ul>
                            <li {% if page =='index1'%} class="active" id="active" {% endif %}>
                                <a href="index.html" class="sub-list">
                                    Dashboard 1
                                </a>
                            </li>
                            <li  {% if page =='index2'%} class="active" id="active" {% endif %}>
                                <a href="index2.html" class="sub-list">
                                    Dashboard 2
                                </a>
                            </li>
                            <li  {% if page =='index3'%} class="active" id="active" {% endif %}>
                                <a href="index3.html" class="sub-list">
                                    Dashboard 3
                                </a>
                            </li>
                        </ul>
                    </li>
                    <li class="main-menu">
                        <a href="javascript:void(0)" class="menu-list text-center {% if (page == 'generalComponents') or (page == 'Navbars') or (page == 'fileUpload') or (page == 'GridView') or (page == 'buttons') or (page == 'RadioCheckbox') or (page == 'dateTimePicker')
                        or (page == 'cards') or (page == 'advancedCards') or (page == 'draggableCards') or (page == 'alerts') or (page == 'advancedAlerts') or (page == 'SweetAlert') or (page == 'Modals')  or (page == 'calendar')
                        or (page == 'gallery') or (page == 'VideoGallery') or (page == 'flippingGallery') or (page == 'fancygallery') %} active{% endif %}">
                            <p><span class="ti-paint-bucket font_18 text-danger"> </span></p> Components
                        </a>
                        <ul>
                            <li>
                                <a href="javascript:void(0)" class="sub-list {% if (page == 'generalComponents') or (page == 'Navbars') or (page == 'fileUpload') or (page == 'GridView') or (page == 'buttons') or (page == 'RadioCheckbox') or (page == 'dateTimePicker') %} active{% endif %}">UI Components</a>
                                <ul>
                                    <li {% if page =='generalComponents'%} class="active" id="active" {% endif %}>
                                        <a href="general_components.html">
                                            General Components
                                        </a>
                                    </li>
                                    <li {% if page =='Navbars'%} class="active" id="active" {% endif %}>
                                        <a href="navbars.html">
                                            Navbars
                                        </a>
                                    </li>
                                    <li {% if page =='fileUpload'%} class="active" id="active" {% endif %}>
                                        <a href="file_upload.html">
                                            File Uploads
                                        </a>
                                    </li>
                                    <li {% if page =='GridView'%} class="active" id="active" {% endif %}>
                                        <a href="grid_view.html">
                                            Grid View
                                        </a>
                                    </li>

                                    <li {% if page =='buttons'%} class="active" id="active" {% endif %}>
                                        <a href="buttons.html">
                                            Buttons
                                        </a>
                                    </li>
                                    <li {% if page =='RadioCheckbox'%} class="active" id="active" {% endif %}>
                                        <a href="radio_checkbox.html">
                                            Radio and Checkboxes
                                        </a>
                                    </li>
                                    <li {% if page =='dateTimePicker'%} class="active" id="active" {% endif %}>
                                        <a href="datetime_picker.html">
                                            Datetime Picker
                                        </a>
                                    </li>

                                </ul>
                            </li>


                            <li>
                                <a href="javascript:void(0)" class="sub-list {% if (page == 'cards') or (page == 'advancedCards') or (page == 'draggableCards') %} active{% endif %}">Cards</a>
                                <ul>
                                    <li {% if page =='cards'%} class="active" id="active" {% endif %}>
                                        <a href="cards.html">
                                            Basic Cards
                                        </a>
                                    </li>
                                    <li {% if page =='advancedCards'%} class="active" id="active" {% endif %}>
                                        <a href="advanced_cards.html">
                                            Advanced Cards
                                        </a>
                                    </li>
                                    <li {% if page =='draggableCards'%} class="active" id="active" {% endif %}>
                                        <a href="draggable_cards.html">
                                            Draggable Cards
                                        </a>
                                    </li>
                                </ul>
                            </li>
                            <li>
                                <a href="javascript:void(0)" class="sub-list {% if (page == 'alerts') or (page == 'advancedAlerts') or (page == 'SweetAlert') %} active{% endif %}"> Alerts</a>
                                <ul>
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

                            <li {% if page =='Modals'%} class="active" id="active" {% endif %}>
                                <a href="modals.html">
                                    Modals
                                </a>
                            </li>
                            <li {% if page =='calendar'%} class="active" id="active" {% endif %}>
                                <a href="calendar.html">
                                    Calendar
                                </a>
                            </li>
                            <li>
                                <a href="javascript:void(0)" class="sub-list {% if (page == 'gallery') or (page == 'VideoGallery') or (page == 'flippingGallery') or (page == 'fancygallery') %}  active{% endif %}"> Galleries</a>
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

                        </ul>
                    </li>
                    <li class="main-menu">
                        <a href="javascript:void(0)" class="menu-list text-center {% if (page == 'basicFormElements') or (page == 'advancedFormElements') or (page == 'AdvancedFormElements2') or (page == 'Summernote') or (page == 'Tinymce')
                      or (page == 'formlayouts') or (page == 'formWizards') or (page == 'formValidation') %} active{% endif %}">
                            <p><span class="ti-view-list font_18 text-warning"> </span></p>  Forms
                        </a>
                        <ul>
                            <li>
                                <a href="javascript:void(0)" class="sub-list {% if (page == 'basicFormElements') or (page == 'advancedFormElements') or (page == 'AdvancedFormElements2') %} active{% endif %}">Form Elements</a>
                                <ul>
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
                            <li>
                                <a href="javascript:void(0)" class="sub-list {% if (page == 'Summernote') or (page == 'Tinymce')%} active{% endif %}"> Form Editors</a>
                                <ul>
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
                                    Form Layouts
                                </a>
                            </li>

                            <li {% if page =='formWizards'%} class="active" id="active" {% endif %}>
                                <a href="form_wizards.html">
                                    Form Wizards
                                </a>
                            </li>
                            <li {% if page =='formValidation'%} class="active" id="active" {% endif %}>
                                <a href="form_validation.html">
                                    Form Validations
                                </a>
                            </li>
                        </ul>
                    </li>
                    <li class="main-menu">
                        <a href="javascript:void(0)" class="menu-list text-center {% if (page == 'ThemifyIcons') or (page == 'fontawesomeIcons') or (page == 'IonIcons') or (page == 'LineIcons') or (page == 'VaadinIcons') or (page == 'SimpleTables') or (page == 'fooTables')
                         or (page == 'SimpleDatatables') or (page == 'datatables') or (page == 'advancedDatatables') or (page == 'colorPalette') or (page == 'Typography') or (page == 'animations') or (page == 'Swiper') or (page == 'PricingTable') or (page == 'JStree')
                          or (page == 'Slider') or (page == 'gridStack') or (page == 'cropper')%} active{% endif %}">
                            <p><span class="ti-brush font_18 text-danger"> </span></p> UI Features
                        </a>
                        <ul>
                            <li>
                                <a href="javascript:void(0)" class="sub-list {% if (page == 'ThemifyIcons') or (page == 'fontawesomeIcons') or (page == 'IonIcons') or (page == 'LineIcons') or (page == 'VaadinIcons') %} active{% endif %}">Icons</a>
                                <ul class="sub-menu">
                                    <li {% if page =='ThemifyIcons'%} class="active" id="active" {% endif %}>
                                        <a href="themify_icons.html">
                                            Themify Icons
                                        </a>
                                    </li>
                                    <li {% if page =='fontawesomeIcons'%} class="active" id="active" {% endif %}>
                                        <a href="fontawesome_icons.html">
                                            Fontawesome Icons
                                        </a>
                                    </li>

                                    <li {% if page =='IonIcons'%} class="active" id="active" {% endif %}>
                                        <a href="ion_icons.html">
                                            Ion Icons
                                        </a>
                                    </li>
                                    <li {% if page =='LineIcons'%} class="active" id="active" {% endif %}>
                                        <a href="simple_line_icons.html">
                                            Simple Line Icons
                                        </a>
                                    </li>
                                    <li {% if page =='VaadinIcons'%} class="active" id="active" {% endif %}>
                                        <a href="vaadin_icons.html">
                                            Vaadin Icons
                                        </a>
                                    </li>
                                </ul>
                            </li>

                            <li>
                                <a href="javascript:void(0)" class="sub-list {% if (page == 'SimpleTables') or (page == 'fooTables') %}  active{% endif %}">Tables</a>
                                <ul class="sub-menu">
                                    <li {% if page =='SimpleTables'%} class="active" id="active" {% endif %}>
                                        <a href="simple_tables.html">
                                            Simple tables
                                        </a>
                                    </li>
                                    <li {% if page =='fooTables'%} class="active" id="active" {% endif %}>
                                        <a href="foo_tables.html">
                                            Foo Tables
                                        </a>
                                    </li>
                                </ul>
                            </li>
                            <li>
                                <a href="javascript:void(0)" class="sub-list {% if (page == 'SimpleDatatables') or (page == 'datatables') or (page == 'advancedDatatables') %}  active{% endif %}">Data Tables</a>
                                <ul class="sub-menu">
                                    <li {% if page =='SimpleDatatables'%} class="active" id="active" {% endif %}>
                                        <a href="simple_datatables.html">
                                            Simple Datatables
                                        </a>
                                    </li>
                                    <li {% if page =='datatables'%} class="active" id="active" {% endif %}>
                                        <a href="datatables.html">
                                            Datatables
                                        </a>
                                    </li>
                                    <li {% if page =='advancedDatatables'%} class="active" id="active" {% endif %}>
                                        <a href="advanced_datatables.html">
                                            Advanced Datatables
                                        </a>
                                    </li>
                                </ul>
                            </li>
                            <li>
                                <a href="javascript:void(0)" class="sub-list {% if (page == 'colorPalette') or (page == 'Typography') or (page == 'animations') or (page == 'Swiper') or (page == 'PricingTable') or (page == 'JStree') %}  active{% endif %}">More Features</a>
                                <ul class="sub-menu">
                                    <li {% if page =='colorPalette'%} class="active" id="active" {% endif %}>
                                        <a href="color_palette.html">
                                            Color Palette
                                        </a>
                                    </li>
                                    <li {% if page =='Typography'%} class="active" id="active" {% endif %}>
                                        <a href="typography.html">
                                            Typography
                                        </a>
                                    </li>

                                    <li {% if page =='animations'%} class="active" id="active" {% endif %}>
                                        <a href="animations.html">
                                            Animations
                                        </a>
                                    </li>

                                    <li {% if page =='Swiper'%} class="active" id="active" {% endif %}>
                                        <a href="swiper.html">
                                            Swiper
                                        </a>
                                    </li>
                                    <li {% if page =='PricingTable'%} class="active" id="active" {% endif %}>
                                        <a href="pricing_table.html">
                                            Pricing Tables
                                        </a>
                                    </li>
                                    <li {% if page =='JStree'%} class="active" id="active" {% endif %}>
                                        <a href="jstree.html">
                                            Js tree
                                        </a>
                                    </li>
                                </ul>
                            </li>
                            <li {% if page =='Slider'%} class="active" id="active" {% endif %}>
                                <a href="sliders.html">
                                    Sliders
                                </a>
                            </li>
                            <li {% if page =='gridStack'%} class="active" id="active" {% endif %}>
                                <a href="grid_stack.html">
                                    Grid Stack
                                </a>
                            </li>
                            <li {% if page =='cropper'%} class="active" id="active" {% endif %}>
                                <a href="cropper.html">
                                    Cropper
                                </a>
                            </li>
                        </ul>
                    </li>
                    <li class="main-menu">
                        <a href="javascript:void(0)" class="menu-list text-center {% if (page == 'lineEcharts') or (page == 'barEcharts') or (page == 'pieEcharts') or (page == 'MorrisCharts') or (page == 'SparklineChart')
                          or (page == 'LineChartist') or (page == 'barChartist') or (page == 'PieChartist') or (page == 'c3LineChart') or (page == 'c3BarChart') or (page == 'NDV3Charts') or (page == 'Rickshaw')
                           or (page == 'flotLineCharts') or (page == 'flotBarCharts') or (page == 'flotPieCharts') or (page == 'LineAmcharts') or (page == 'columnBarAmcharts') or (page == 'PieFunnelAmcharts')
                            or (page == 'gaugeAmcharts') or (page == 'PerityCharts') or (page == 'chartJs') %}  active{% endif %}">
                            <p><span class="ti-pie-chart font_18 text-info"> </span></p> Charts
                        </a>
                        <ul>
                            <li>
                                <a href="javascript:void(0)" class="sub-list {% if (page == 'lineEcharts') or (page == 'barEcharts') or (page == 'pieEcharts') %}  active{% endif %}">E Charts</a>
                                <ul>
                                    <li {% if page =='lineEcharts'%} class="active" id="active" {% endif %}>
                                        <a href="echart_line.html">
                                            Line Echarts
                                        </a>
                                    </li>
                                    <li {% if page =='barEcharts'%} class="active" id="active" {% endif %}>
                                        <a href="echart_bar.html">
                                            Bar Echarts
                                        </a>
                                    </li>
                                    <li {% if page =='pieEcharts'%} class="active" id="active" {% endif %}>
                                        <a href="echart_pie.html">
                                            Pie Ecahrts
                                        </a>
                                    </li>
                                </ul>
                            </li>


                            <li {% if page =='MorrisCharts'%} class="active" id="active" {% endif %}>
                                <a href="morris_chart.html" class="sub-list">
                                    Morris Charts
                                </a>
                            </li>
                            <li {% if page =='SparklineChart'%} class="active" id="active" {% endif %}>
                                <a href="sparkline_charts.html" class="sub-list">
                                    Sparkline Charts
                                </a>
                            </li>
                            <li>
                                <a href="javascript:void(0)" class="sub-list {% if (page == 'LineChartist') or (page == 'barChartist') or (page == 'PieChartist') %}  active{% endif %}">Chartist</a>
                                <ul>
                                    <li {% if page =='LineChartist'%} class="active" id="active" {% endif %}>
                                        <a href="line_chartist.html">
                                            Line Chartist
                                        </a>
                                    </li>
                                    <li {% if page =='barChartist'%} class="active" id="active" {% endif %}>
                                        <a href="bar_chartist.html">
                                            Bar Chartist
                                        </a>
                                    </li>
                                    <li {% if page =='PieChartist'%} class="active" id="active" {% endif %}>
                                        <a href="pie_chartist.html">
                                            Pie Chartist
                                        </a>
                                    </li>
                                </ul>
                            </li>
                            <li>
                                <a href="javascript:void(0)" class="sub-list {% if (page == 'c3LineChart') or (page == 'c3BarChart') %}  active{% endif %}"> C3 Charts</a>
                                <ul>
                                    <li {% if page =='c3LineChart'%} class="active" id="active" {% endif %}>
                                        <a href="c3_line_chart.html">
                                            C3 Line Charts
                                        </a>
                                    </li>
                                    <li {% if page =='c3BarChart'%} class="active" id="active" {% endif %}>
                                        <a href="c3_bar_chart.html">
                                            C3 Bar Charts
                                        </a>
                                    </li>
                                </ul>
                            </li>


                            <li {% if page =='NDV3Charts'%} class="active" id="active" {% endif %}>
                                <a href="nvd3_charts.html" class="sub-list">
                                    NVD3 Charts
                                </a>
                            </li>
                            <li {% if page =='Rickshaw'%} class="active" id="active" {% endif %}>
                                <a href="rickshaw.html" class="sub-list">
                                    Rickshaw
                                </a>
                            </li>
                            <li>
                                <a href="javascript:void(0)" class="sub-list {% if (page == 'flotLineCharts') or (page == 'flotBarCharts') or (page == 'flotPieCharts') %}  active{% endif %}">Flot Charts</a>
                                <ul>
                                    <li {% if page =='flotLineCharts'%} class="active" id="active" {% endif %}>
                                        <a href="flot_line_charts.html">
                                            Flot Line Charts
                                        </a>
                                    </li>
                                    <li {% if page =='flotBarCharts'%} class="active" id="active" {% endif %}>
                                        <a href="flot_bar_charts.html">
                                            Flot Bar Charts
                                        </a>
                                    </li>
                                    <li {% if page =='flotPieCharts'%} class="active" id="active" {% endif %}>
                                        <a href="flot_pie_charts.html">
                                            Flot Pie Charts
                                        </a>
                                    </li>
                                </ul>
                            </li>
                            <li>
                                <a href="javascript:void(0)" class="sub-list {% if (page == 'LineAmcharts') or (page == 'columnBarAmcharts') or (page == 'PieFunnelAmcharts') or (page == 'gaugeAmcharts') %}  active{% endif %}">Amcharts</a>
                                <ul>
                                    <li {% if page =='LineAmcharts'%} class="active" id="active" {% endif %}>
                                        <a href="line_amcharts.html">
                                            Line Amcharts
                                        </a>
                                    </li>
                                    <li {% if page =='columnBarAmcharts'%} class="active" id="active" {% endif %}>
                                        <a href="column_bar_amcharts.html">
                                            Bar Amcharts
                                        </a>
                                    </li>
                                    <li {% if page =='PieFunnelAmcharts'%} class="active" id="active" {% endif %}>
                                        <a href="pie_funnel_amcharts.html">
                                            Pie Funnel Amcharts
                                        </a>
                                    </li>
                                    <li {% if page =='gaugeAmcharts'%} class="active" id="active" {% endif %}>
                                        <a href="gauge_amcharts.html">
                                            Gauge Amcharts
                                        </a>
                                    </li>
                                </ul>
                            </li>
                            <li {% if page =='PerityCharts'%} class="active" id="active" {% endif %}>
                                <a href="peity_charts.html" class="sub-list">
                                    Peity Charts
                                </a>
                            </li>
                            <li {% if page =='chartJs'%} class="active" id="active" {% endif %}>
                                <a href="chartjs.html" class="sub-list">
                                    Chartjs
                                </a>
                            </li>
                        </ul>
                    </li>
                    <li class="main-menu">
                        <a href="javascript:void(0)" class="menu-list text-center {% if (page == 'Widgets1') or (page == 'Widgets2') or (page == 'Widgets3') or (page == 'Inbox') or (page == 'SentMail') or (page == 'emailView') or (page == 'compose') or (page == 'drafts') or (page == 'Trash') or (page == 'allMails')
                          or (page == 'Profile1') or (page == 'Profile2') or (page == 'UserList') or (page == 'addUser') or (page == 'deleteuser')
                           or (page == 'basicGmaps') or (page == 'gmapServices') or (page == 'gmapRoutes') or (page == 'gmapUtils') or (page == 'vectormaps')
                            or (page == 'Timeline1') or (page == 'Timeline2') or (page == 'Notifications') or (page == 'Notifications2') or (page == 'PNotify')
                            or (page == 'Transitions') or (page == 'Rating') %} active{% endif %}">
                           <p><span class="ti-desktop font_18 text-success"> </span></p> UI
                        </a>
                        <ul>
                            <li>
                                <a href="javascript:void(0)" class="sub-list {% if (page == 'Widgets1') or (page == 'Widgets2') or (page == 'Widgets3')  %} active{% endif %}">Widgets</a>
                                <ul>
                                    <li {% if page =='Widgets1'%} class="active" id="active" {% endif %}>
                                        <a href="widgets1.html">
                                            Widgets 1
                                        </a>
                                    </li>
                                    <li {% if page =='Widgets2'%} class="active" id="active" {% endif %}>
                                        <a href="widgets2.html">
                                            Widgets 2
                                        </a>
                                    </li>
                                    <li {% if page =='Widgets3'%} class="active" id="active" {% endif %}>
                                        <a href="widgets3.html">
                                            Widgets 3
                                        </a>
                                    </li>
                                </ul>
                            </li>
                            <li>
                                <a href="javascript:void(0)" class="sub-list {% if (page == 'Inbox') or (page == 'SentMail') or (page == 'emailView') or (page == 'compose') or (page == 'drafts') or (page == 'Trash') or (page == 'allMails') %} %}  active{% endif %}">Emails</a>
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
                            <li>
                                <a href="javascript:void(0)" class="sub-list {% if (page == 'Profile1') or (page == 'Profile2') or (page == 'UserList') or (page == 'addUser') or (page == 'deleteuser')%}  active{% endif %}">Users</a>
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

                            <li>
                                <a href="javascript:void(0)" class="sub-list {% if (page == 'basicGmaps') or (page == 'gmapServices') or (page == 'gmapRoutes') or (page == 'gmapUtils') or (page == 'vectormaps') %}  active{% endif %}">Maps</a>
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
                                    <li {% if page =='vectormaps'%} class="active" id="active" {% endif %}>
                                        <a href="vectormaps.html">
                                            <i class="ti-angle-double-right"></i> Vector Maps
                                        </a>
                                    </li>
                                </ul>
                            </li>

                            <li>
                                <a href="javascript:void(0)" class="sub-list  {% if (page == 'Timeline1') or (page == 'Timeline2')  %} active{% endif %}">Timeline</a>
                                <ul class="sub-menu">
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
                            <li>
                                <a href="javascript:void(0)" class="sub-list  {% if (page == 'Notifications') or (page == 'Notifications2') or (page == 'PNotify')  %} active{% endif %}">Notifications</a>
                                <ul class="sub-menu">
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
                            <li {% if page =='Transitions'%} class="active" id="active" {% endif %}>
                                <a href="transitions.html">
                                    Transitions
                                </a>
                            </li>
                            <li {% if page =='Rating'%} class="active" id="active" {% endif %}>
                                <a href="rating.html">
                                    Ratings
                                </a>
                            </li>
                        </ul>
                    </li>
                    <li class="main-menu">
                        <a href="javascript:void(0)" class="menu-list text-center {% if (page == 'blank') or (page == 'Invoice') %} active{% endif %}">
                            <p><span class="ti-files font_18 text-warning"> </span></p>  Pages
                        </a>
                        <ul>
                            <li {% if page =='blank'%} class="active" id="active" {% endif %}>
                                <a href="blank.html" class="sub-list">
                                    Blank
                                </a>
                            </li>
                            <li>
                                <a href="login.html" class="sub-list">
                                    Login
                                </a>
                            </li>
                            <li>
                                <a href="register.html" class="sub-list">
                                    Register
                                </a>
                            </li>
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
                </ul>
            </div>
        </div>
    </div>
</div>
```

