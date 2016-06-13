Visual Studio Dark Theme for IDEA Intelliji
============================================

A replica of Visual Studio's dark theme for Intelliji.

![Example with Groovy](/screenshots/groovy.png)

## Installation

### Automatic

- Download settings.jar
- In Intelliji, go to File -> Import Settings
- Select the settings.jar file you downloaded and press OK.

Intelliji will then restart before applying the color theme. If the theme is not atomatically applied, go to File -> Settings and then Editor -> Colors & Fonts and select the theme manually (Visual Studio 2015).

### Manual

Download Visual Studio 2015.icls. Place it in:

- **Windows:** `C:\<username>\<Intelliji Folder>\config\colors\`
- **Mac:** `~/Library/Preferences/<Intelliji Folder>/colors`
- **Linux:** `~/<Intelliji Folder>`

\`Intelliji Folder\` will be something like \`.IntelliJIdea2016.1\`. For more information, see the [Intelliji help page](https://www.jetbrains.com/help/idea/2016.1/directories-used-by-intellij-idea-to-store-settings-caches-plugins-and-logs.html?origin=old_help).

Then select the theme in File -> Settings and then Editor -> Colors & Fonts.

## Supported Languages

Currently, the theme will work with:

- Java
- Groovy
- kotlin
- HTML, CSS, Less, Sass/SCSS
- Javascript, Typescript and CoffeeScript, 
- Templating Languages (GSP, JSP...)
- Actionscript
- Batch Script
- Cucumber
- SQL
- XML and XSLT
- JSON and YAML

and some others. Python support is currently being worked on.
