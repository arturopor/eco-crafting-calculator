# Eco Crafter

# Contributing
## Adding/Updating Items
I am using [ObjGen](https://beta5.objgen.com/json/) for now because it's an easier format to type up the object data in. Sort the resulting json by name, then category. Sorting the list saves me from doing it at runtime on every client's page load.

To update the [`src/items.json`](src/items.json) file please follow these steps.
1. Update [`src/itemObjGen.txt`](src/itemObjGen.txt).
2. Run `npm run objgen`.
