Delegate AjaxMin Builder

A simple nuget package to add MSBuild targets to be able to utilize the excellent AjaxMin tool from Microsoft (http://ajaxmin.codeplex.com) to bundle and/or minify CSS and JS files during build in your Visual Studio projects. 

It requires you to create .ajaxmin (or .ajaxmin.xml) files in your project where you want to bundle/minify files. Include the ajaxmin files in your Visual Studio project and it will be build during compilation. File format is specified at: http://ajaxmin.codeplex.com/wikipage?title=XML%20File%20Formats. 

No external binary dependencies. No dll references will be added to your project.

Tested with Visual Studio 2013.


Works well with package restore on a build server too, though you need to do the package restore as described here https://docs.nuget.org/consume/package-restore/team-build.


Enjoy!

Søren Laurits Nielsen (sln@delegate.dk)
