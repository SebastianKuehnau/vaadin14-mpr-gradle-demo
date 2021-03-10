# Demo for Vaadin 19 Application with MPR and Spreadsheet Addon for Vaadin 8 build with Gradle

This project contains an example configuration with Spreadsheet for Vaadin 8 integrated with Multi Platform Runtime in a Vaadin 19 Application. It has been adjusted from the given example (https://gitlab.com/mvysny/vaadin14-mpr-gradle-demo) of my colleague at Vaadin Martin Vysny, where the project is built with kotlin and without the spreadsheet component.

One example sheet is load for Spreadsheet in a view named "spreadsheet" and the content is shown in the component itself.

To build the application you can use the added gradle wrapper (`./gradlew build`) or a local installed gradle 6+ (`gradle build`). In addition, a vaadin prime license (https://vaadin.com/pricing) is also necessary.

The application can be run with `./gradlew appRun` or respectively `gradle appRun`.