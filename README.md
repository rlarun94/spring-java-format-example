# spring-java-format-example
application to describe Spring Java Code Format option 

Handles below:
A source formatter that applies wrapping and whitespace conventions
A checkstyle plugin that enforces consistency across a codebase

Need to add below plugin in the pom.xml file. It will format the code automatically.

Intellij: Maven section --> expand the Plugins--> you will be able to see formatter plugin
-- select validate --> it will throw exception when there is spacing issue
-- select fix apply --> this will fix the formatter issues across the project
