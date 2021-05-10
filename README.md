# 2rooms
Two rooms in a session where one room broadcasts key information for the next room to build on.
Consider the first room creating product information and the next room creating bill of materials with those materials.
first room broadcasts information as object 
{
material:material, 
description: description,
unit: unit,
mattype: mattype
}

Using this broadcast the second room creates teh bill of materials.

A simple example of collaborating process in a session.

The process needs three rooms

1. main - room where everyone joins at first
2. mat  - room where products are created
3. bom - room where bill of material is created
