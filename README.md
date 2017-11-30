# HackSand-Ridge
Application source code has all 3rd-part javascript files already included.  There are no cdnet links necessary within the index.html file.
The application uses C# .NET 4.5 code as well as javascript.  The javascript platform is AngularJS version 1x.
This application is best built and deployed by using Visual Studio IDE.  Open the project within the VS environment and right-click the project name.  On the context menu, click Build.  This methodology is best used for both the web application as well as the console application for the arduino device.
To deploy this application, the best practice would be to use Azure (if using, ensure there is a web server available for deployment).  Other methods are through file publish and copy to IIS or through IIS publish.
The current web application can be accessed through http://sdhackathon.azurewebsites.net.  When deploying locally, the access will be from the website name and location designated by the developer.  To use the arduino console application, build this console application and deploy to the computer where the arduino is attached.
Finally, open the SQLScripts file within SSMS and execute to create the tables necessary for the application to write to.
