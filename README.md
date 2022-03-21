# Meal Ordeal

## Summary

Meal Ordeal is an action-RPG game produced with Godot Engine 4 for a Final Major Project.
The game follows the adventures of a young adult struggling with finances, Jess Brooks.

The gameplay revolves around Jess working in a deli shop, filling in daily quota, paying off debts and ultimately breaking out of the corporate hell landscape.

## Project naming conventions

- `Variables`       : lower_snake_case, as descriptive as possible, no abbreviations unless easy to understand.
- `Constants`       : UPPER_SNAKE_CASE, as descriptive as possible, no abbreviations unless easy to understand.
- `Enums and Nodes` : PascalCase, simple nouns, adjectives only if necessary.
- `Assets` : all lowercase, no _ or -
  - `Sprites` : prefixed with `sp_`
  - `Textures, Images` : prefixed with `res_`
  - `Sound Effects` : prefixed with `sfx_`
  - `Music Files`   : prefixed with `mus_`

## Folder structure example
  - src *(source)*
    - player
      - ...
    - enemy
    - item 
    - world
      - world1
      - world2
      - ...
    - core
      - actor
      - shooter
      - ...  

The followed convention in terms of folder organization is context-based, instead of asset type based. Asset type organization causes redundancies between naming conventions and folder structure.

## Additional conventions

- When typing static data (databases, dictionaries, large arrays, large constructors) it is prefferable to format that data as a table.
- Every commit should describe the actions performed, and detail the possible consequences of that action.
