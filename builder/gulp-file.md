# Add Builder

We are using nunjucks builder it is very easy to use.

It has the following Staps:

1. We have to add    `"gulp-nunjucks-render" : "^2.0.0"` in package.json as dependencies.
2. **gulpfile.js:**

   We have to declare below global variables:

   `var nunjucksRender = require('gulp-nunjucks-render');    
   var units1 = process.argv[2];    
   var units2 = process.argv[3];    
   var units3 = process.argv[4];`

   `var inputTemplates = resourcesAssets + 'pages/*.html' ;`

   `var siteOutput = './' ;`

   We have to declare function:

   `gulp.task('nunjucks', function() {    
   var layout;    
   var bc;    
   if (units1&&units2&&units3&&units1=="nunjucks")    
   {    
   layout=units2.substring(2);    
   bc=units3.substring(2);    
   }    
   return gulp.src(inputTemplates)    
   .pipe(nunjucksRender({    
   path:['src/templates/'],    
   data:{layout:layout, bc:bc}    
   }))    
   .pipe(gulp.dest(siteOutput))    
   });`

   And call the function :

   `elixir(function(mix)    
   {    
   //nunjucks    
   mix.task('nunjucks');    
   });`

