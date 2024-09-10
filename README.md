# Visual Studio 2022:
There should be an Option somewhere in the ide to add a custom json catalog.
Tools>Options>Json>Schema
Then click add new one in the upper left.
Copy this link:
####
    https://raw.githubusercontent.com/SirNoName2705/Vintellisense/master/Schemas/current/vs_schema_catalog.json
and paste it in the settings.
Save and restart the ide.

# Rider
- Download the JsonSchemas.xml of your choice. ([url](https://raw.githubusercontent.com/SirNoName2705/JsonSchemaGenerator/master/SchemaDirectOutput/urlSettings/jsonSchemas.xml) or [local](https://raw.githubusercontent.com/SirNoName2705/JsonSchemaGenerator/master/SchemaDirectOutput/localSettings/jsonSchemas.xml) version)
- Then put it in the .idea/.idea.__ProjectName__.dir/.idea folder (that is the .idea folder of the project not the solution)
- If you use the local version you also need to put the .schemas folder in the main directory

# VsCode
- Download the settings.json of your choice. ([url](https://raw.githubusercontent.com/SirNoName2705/JsonSchemaGenerator/master/SchemaDirectOutput/urlSettings/settings.json) or [local](https://raw.githubusercontent.com/SirNoName2705/JsonSchemaGenerator/master/SchemaDirectOutput/localSettings/settings.json) version)
- Put the file in your .vscode folder
- If you use the local version you also need to put the .schemas folder in the main directory




Credits:
- DarkhNekromant for the idea and a lot of the code.
- Th3Dilli for helping me to understand vintage story
