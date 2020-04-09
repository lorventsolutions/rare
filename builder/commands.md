# Commands

Commands for different layouts

To generate files, you need to run following command

gulp nunjucks --**layout style** &lt;space&gt; --**breadcrum style**

ex: `gulp nunjucks --layout default --breadcrumb 0 --color primary`

Following table explains all available layouts and the command to use,

please note that you need to pass 0 to 5... one of the breadcrumb styles along with layout command.

| Layout Name | Command | Layout Image |
| :--- | :--- | :---: |
| default | gulp nunjucks --layout default --breadcrumb \(0 to 5\) --color \* | ![](../.gitbook/assets/rare82_sm.PNG) |
| compact menu | gulp nunjucks --layout compact-menu --breadcrumb \(0 to 5\) --color \* | ![](../.gitbook/assets/rare81_sm.PNG) |
| centered logo | gulp nunjucks --layout centered-logo --breadcrumb \(0 to 5\) --color \* | ![](../.gitbook/assets/rare80_sm.PNG) |
| horizontal menu | gulp nunjucks --layout horizontal-layout --breadcrumb \(0 to 5\) --color \* | ![](../.gitbook/assets/rare72_sm.PNG) |
| icon horizontal menu | gulp nunjucks --layout icon-horizontal --breadcrumb \(0 to 5\) --color \* | ![](../.gitbook/assets/rare73_sm.PNG) |
| fixed menu | gulp nunjucks --layout fixed-menu --breadcrumb \(0 to 5\) --color \* | ![](../.gitbook/assets/rare74_sm.PNG) |
| fixed header | gulp nunjucks --layout fixed-header --breadcrumb\(0 to 5\) --color \* | ![](../.gitbook/assets/rare75_sm.PNG) |
| full width | gulp nunjucks --layout fullwidth-layout --breadcrumb \(0 to 5\) --color \* | ![](../.gitbook/assets/rare76_sm.png) |
| fixed footer | gulp nunjucks --layout fixed-footer --breadcrumb \(0 to 5\) --color \* | ![](../.gitbook/assets/rare79_sm.PNG) |
| dark layout | gulp nunjucks --layout dark-layout --breadcrumb \(0 to 5\) --color \* | ![](../.gitbook/assets/rare78_sm.PNG) |
| header style1 | gulp nunjucks --layout header-style1 --breadcrumb \(0 to 5\) --color \* | ![](../.gitbook/assets/rare77_sm.PNG) |
| Mmenu | gulp nunjucks --layout mmenu --breadcrumb \(0 to 5\) --color \* | ![](../.gitbook/assets/mmenu.png) |
| Light Sidebar | gulp nunjucks --layout light-sidebar --breadcrumb \(0 to 5\) --color \* | ![](../.gitbook/assets/light_sidebar.png) |

Where`--color *` is

`--color default`

`--color primary`

`--color success`

`--color danger`

`--color mint`

`--color purple`

