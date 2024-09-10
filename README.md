# Installation

## Visual Studio 2022:
There should be an Option somewhere in the ide to add a custom json catalog.
Tools>Options>Json>Schema
Then click add new one in the upper left.
Copy this link:
####
    https://raw.githubusercontent.com/SirNoName2705/VintelliSchemas/master/SchemaReleases/current/vs_schema_catalog.json
and paste it in the settings. This version requires less manual intervention after installation

## Rider
- Download the JsonSchemas.xml [here](https://raw.githubusercontent.com/SirNoName2705/VintelliSchemas/master/SchemaReleases/current/jsonSchemas.xml)
- Then put it in the .idea/.idea.__ProjectName__.dir/.idea folder (that is the .idea folder of the project not the solution)
- If you use the local version you also need to put the .schemas folder in the main directory

## VsCode
- Download the settings.json [here](https://raw.githubusercontent.com/SirNoName2705/VintelliSchemas/master/SchemaReleases/current/settings.json)
- Put the file in your .vscode folder
- If you use the local version you also need to put the .schemas folder in the main directory

# Features
For detailed version history, see the [Changelog](CHANGELOG.md)
- 38 JSON Schemas covering key asset types: `entities`, `blocks`, `items`.
- Full support for complex elements like attributes, behaviors, classes, codes, and entity behaviors.



### Todo
- Add how to use section
- Add example images
- Add Roadmap
- Add to Vintage Story mod template
- Write Vintage Story wiki entry
- Write Jetbrains extension for auto update json catalog
- Write VS code extension for auto update json catalog
- 
- 
  Credits:
- DarkhNekromant for the idea and a lot of the code.
- Th3Dilli for helping me to understand vintage story