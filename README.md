Twitter Bootstrap - jQuery Validate
==============================

###What?

This is an integration between two well developed and widely accepted projects.

1.  Twitter Bootstrap - http://twitter.github.io/bootstrap/
2.  jQuery Validate - http://validation.bassistance.de/


###Why?

There are some projects out there that offer validation on top of Twitter Bootstrap's markup, but they start from scratch and the validation options are have that of what jQuery Validate offers. Why reinvent the wheel we can make some minor modifications to jQuery Validate to support the Twitter Boootstrap markup? That is what this project does.

###How?

Implementation is very easy.

[Here](http://www.pknopf.com/TwitterBootstrapjQueryValidate/Scripts/jquery.validate.bootstrap.js) is the only script file you need.

You simple need to include this script directly after the reference to jQuery Validate. For example:

    <script src="/Content/Scripts/jquery-2.1.1.js"                  type="text/javascript"></script>
    <script src="/Content/Scripts/jquery.validate.js"               type="text/javascript"></script>
    <script src="/Content/Scripts/jquery.validate.unobtrusive.js"   type="text/javascript"></script>
    <!-- BEGIN: INSERT CUSTOM SCRIPT FILE HERE -->
    <script src="/Content/Scripts/jquery.validate.bootstrap.js"     type="text/javascript"></script>
    <!-- END:   INSERT CUSTOM SCRIPT FILE HERE -->
    
Thats it! The last script modifies the original jQuery Validate framework to handle Twitter Bootstrap markup.

Your welcome!
