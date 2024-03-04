Here are some of the highlights of what IMMARKUS offers.

## Multi-Window Zoomable Image Annotation

IMMARKUS provides a zoomable view to support annotating large images, and tools for creating __rectangle__, __polygon__ and __circle/ellipse__ selections. Similar to multi-image viewers like [Mirador](https://projectmirador.org/), IMMARKUS provides a multi-window environment for annotating multiple images side by side.

<img width="1552" alt="Bildschirmfoto 2024-01-16 um 16 12 23" src="https://github.com/rsimon/immarkus/assets/470971/ebf70929-ee30-462a-9f5e-7bded3d5f827">

Read more about [Annotating Multiple Images Simultaneously](https://github.com/rsimon/immarkus/wiki/04-Annotating-Images#annotating-multiple-images-simultaneously)

## Design Your Own Ontology

IMMARKUS includes a form-based editor to create and manage your personal data model. The data model is designed around the concepts of **Entity Classes** and **Properties**.

- Use __Entity Classes__ to annotate specific concepts or things with your annotations.
- Define __Properties__ for your Entity Classes, to record specific details in your annotations, such as location, dimension, materials, etc. of an entity.
- Your data model can be __hierarchical__. Each entity class can have a parent class. Properties on the parent class are automatically inherited to the child class. This way, you are building your own personal knowledge graph for your content.

<img width="800" alt="Bildschirmfoto 2024-01-16 um 15 17 21" src="https://github.com/rsimon/immarkus/assets/470971/cd8ced9f-3a82-482a-9f55-d750771a456b">

Read more about [Design a Data Model](https://github.com/rsimon/immarkus/wiki/03-Designing-a-Data-Model)

## Property Types

IMMARKUS offers a range of data types you can use to capture properties of different kinds. Think of it as a personal "database builder" for your data model. The following Property field types are currently available:

- Text 
- Number
- Select options dropdown with configurable values
- URL/URI
- Geo-coordinate
- Measurement (combination of numeric value and "unit" text field)
- External authority (read more [here](https://github.com/rsimon/immarkus/wiki/04-Annotating-Images#using-external-authorities-in-annotations))

<img width="800" alt="Bildschirmfoto 2024-01-16 um 16 03 15" src="https://github.com/rsimon/immarkus/assets/470971/d7ee8b44-23f1-4a71-abdf-e8b55eefb4f8">
