# Hi-Framework dev-console

## What is it?
A web console that allows developers to easily:
- Display application configuration in a more readable way
- Display all available routes in the application (controller/action)
- Display all available frontiers
- Configure i18n (mappings, languages and dictionaries)
- Create new template and automatically register
- Enable fixed or smart caching for a specific directory
- Create mock frontiers (select a frontier interface or a frontier class to mock + HiList special support)
- Set fake template data

## How is it added to the project
Including a Jar dependency should be enough. 

## What is inside the dev-console jar
A buch of Controllers with their respective views and frontiers. One of the controllers is **Dev** and it has an action method name **console**. The jar also includes one template.

## How to access it
/dev/console
