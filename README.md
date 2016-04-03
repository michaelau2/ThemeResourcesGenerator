# ThemeResourcesGenerator
ThemeResourcesGenerator is a simple Java application that generates a theme_resources.xml file from the appfilter.xml.

appfilter.xml and theme_resources.xml are two files that are needed by icon packs to apply icons. Nevertheless some icon pack dashboard required them, but only generates appfilter.xml with the in-app request tool.<br>
With this simple tool is possible to generate the theme_resources.xml file from an appfilter.xml file simply with a double click.

#How it works
You just need to put the jar file in the same folder where is located you appfiletr.xml file. Now double click on the jar file and the theme_resources.xml file will magically appear on your folder!

#Download
Downloading the zip directly from Github you will get the .jar file and the Netbeans project.<br>
If you need the .jar file only you can get it <a href="https://mega.nz/#!AU4WUSyC">here</a>.

The code is very simple and commented. I'm not a developer but I did my best. Feel free to improve it ;)

#Note
This tools is perfect if you use it with appfilter.xml files generated with <a href="https://github.com/afollestad/polar-dashboard">Polar Dashboard</a>. These files has some strings at the top of the file that has some extra infos; the tool automatically recognize and replace them with other strings needed by LG Home Launcher. Don't forget to edit them!<br>
If there are not these strings the tool won't add new strings.
