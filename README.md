# mvn-less-css

Parent project for template project to generate custom css with custom less files with maven.

# Overview

This is an example project how to generate custom css with custom less files with the maven tool.
The parent project defines the pluginManagement with the lesscss-maven-plugin which is used to generate the custom css. For more information for the [lesscss-maven-plugin](https://github.com/marceloverdijk/lesscss-maven-plugin) go to the project page.

# How to

To customize for your project there are a two options:

1. You can fork this project and adapt it for your needs.
2. You create a maven project and extend from parent project mvn-parent-projects like the project module simple-tmpl-less does and adapt it for your needs.
