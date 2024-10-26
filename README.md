# recipes

A collection of recipes usable in Homagix

## File format

Recipe files are stored as yaml in the following structure:

```yaml
---
name: title of dish
source: An optional field containing a reference from where the recipe is taken
items:
  - <amount> <unit> <name of ingredient>
  - ...
  - with <amount a decimal number in english notation (optional decimal point '.')
  - and <unit> an ISO (metric) unit (e.g. 'ml' or 'g')
recipe: >-
  Markdown text describing the steps to cook the ingredients to the dish.
images:
  - list of file names, relative to this yaml file. The first file name is taken as the main image
