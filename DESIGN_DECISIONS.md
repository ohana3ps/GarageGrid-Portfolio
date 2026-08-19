# Design Decisions

## Stable identity, flexible labels

Rooms, fixtures, positions, containers, and items receive permanent internal identities. Names such as “Box 20 — Plumbing” remain editable without breaking history or relationships.

## An adaptable spatial model

Real storage is irregular. A rack, freezer, refrigerator, cart, or cabinet can share a common hierarchy while each section retains its own number and arrangement of positions. This accommodates mixed box sizes, drawers, door bins, freezer layers, and open shelf areas.

## Inventory identity versus quantity

A distinct hammer, appliance, or paint can may need its own history and documentation. Identical consumable packages can instead be represented as a counted supply. Quantities can be distributed among locations and reduced one unit at a time.

## Staging belongs to every room

Staging is not merely an “unassigned” database state. It is an intentional workflow and physical concept: items have entered a room but have not reached their final storage position.

## Containers are optional

A shelf position may hold a container, a loose item, or a shared list of items. The physical shelf behaves as a location, not as a disguised container, preserving a clearer model for moves and capacity.

## Checkout preserves context

Checking out an item does not erase where it belongs. The system preserves the original home and accepts a purpose/location note, making both return and “where should I look?” workflows practical.

## Capacity is descriptive

Capacity reflects how a user understands the space: open, partly used, full, or divided into smaller mapped areas. It avoids pretending that every real-world object has uniform dimensions.

## Human review for assisted intake

Barcode databases and image recognition are imperfect. Suggested names, brands, categories, and descriptions remain editable before the user commits the inventory record.

## Progressive disclosure on mobile

Frequently used intake and movement controls appear first. Warranty, model, serial number, condition, and replacement-cost details can remain collapsed until relevant.

## Local-first privacy

The application is designed to run on a private local network for household members. A public code deployment or hosted household database is not required for ordinary use.
