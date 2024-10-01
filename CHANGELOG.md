# Changelog

## [v1.1] - 2024.10.01
### Added
- JsonPatches have autocomplete for mod id and filepath for vanilla game files
- Json Patches has a check to ensure right usage of Move operation
- All Major Schemas now have a Title. (A Major schema is a schemas that has its own file)
- Recipes schemas with array notation

### Changed
- Enum Values are now Case Insensitive
- Replaced many int types with number types
- Fix value property in JsonPatches to allow for any type (This should also fix some other issues where the JsonObject class was used)

## [v1.0] - 2024.09.10
### Added
- 38 JSON Schemas covering key asset types: `entities`, `blocks`, `items`.
- Full support for complex elements like attributes, behaviors, classes, codes, and entity behaviors.

### Missing
- Cooking recipes are not yet included and will be added in the next major release (v2.0).

### Known Issues
- Crafting recipes are partially supported; ingredients do not autocomplete correctly.
- There may be bugs related to asset types that are not `entities`, `blocks`, or `items`.

### Upcoming
- Version v1.2 will focus on crafting recipes with autocomplete support for item and block codes.
