# textAngular-toolbar-customized-with-font-color-font-size-
textAngular-toolbar customized with font,color,font-size 



Demo is available http://embed.plnkr.co/V6ZJS7GdsvRIrpznGbh9/preview


## Requirements
    "angular": "~1.4.6",
    "angular-spectrum-colorpicker": "~1.4.2",
    "bootstrap": "~3.3.5",
    "font-awesome": "~4.4.0",
    "jquery": "~2.1.4",
    "spectrum": "~1.7.1",
    "textAngular": "~1.4.6"
    
 
    **Usage:**
    
   
    
    <!DOCTYPE html>
    <html ng-app="myApp">
    
    <head>
        <link rel="stylesheet" href="../bower_components/textAngular/dist/textAngular.css">
        <link rel="stylesheet" type="text/css" href="../bower_components/spectrum/spectrum.css" />
        <link rel="stylesheet" type="text/css" href="../bower_components/bootstrap/dist/css/bootstrap.min.css">
        <link  rel="stylesheet" href="../bower_components/font-awesome/css/font-awesome.min.css" />
        <link rel="stylesheet" href="css/style.css" />
    </head>
    
    <body>
    <div ng-controller="myCtrl">
        <div text-angular ng-model="html"></div>
    
        <pre ng-bind="html" class="white-box ng-binding"></pre>
    
    </div>
    <script src="../bower_components/jquery/dist/jquery.min.js"></script>
    <script src="../bower_components/angular/angular.min.js"></script>
    <script src="../bower_components/spectrum/spectrum.js"></script>
    <script src="../bower_components/angular-spectrum-colorpicker/dist/angular-spectrum-colorpicker.js"></script>
    <script src="../dist/textAngular-dropdownToggle.js"></script>
    <script src="../bower_components/textAngular/dist/textAngular-rangy.min.js"></script>
    <script src='../bower_components/textAngular/dist/textAngular-sanitize.min.js'></script>
    <script src="../bower_components/textAngular/dist/textAngularSetup.js"></script>
    <script src='../bower_components/textAngular/dist/textAngular.min.js'></script>
    
    
    <script src="../dist/script.js"></script>
    
    </body>
    
    </html>

   
    
    
 