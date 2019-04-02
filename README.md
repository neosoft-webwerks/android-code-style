# Installing the google styleguide settings in intellij/android studio

***Installing the coding style settings in Intellij***

Download the intellij-java-google-style.xml file from the http://code.google.com/p/google-styleguide/ repo.

***Windows***

Copy it into your config/codestyles folder in your IntelliJ settings folder. Under Settings -> Editor -> Code Style select the google-styleguide as current code style for the Metanome project.

***Macintosh***

Download it and go into Preferences -> Editor -> Code Style. Click on Manage and import the downloaded Style Setting file. Select GoogleStyle as new coding style.

# Installing the coding style settings in Eclipse

Download the eclipse-java-google-style.xml file from the http://code.google.com/p/google-styleguide/ repo. Under Window/Preferences select Java/Code Style/Formatter. Import the settings file by selecting Import.

----------
# Neosoft code style for android
The code styles below are strict rules for contributing Java code to the Android project. 

***Please install and configure attached coding style:***

    Open android Studio environment.
    Import settings.jar into Android Studio. It defines our coding style.  

You just need to use ***File -> Import Settings*** option in Android Studio. (Do not add file into project, its for the android studio).

To format the code according to our style, either ***right click on java file/package -> reformat code or ctrl+alt+L.*** (Check optimize imports and rearrange entires).

Please make sure you format the code before committing, this will help us in reducing lot of unnecessary conflicts and improve readability.
