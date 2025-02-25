Here are some of the highlights of what IMMARKUS offers.

## Multi-Window Zoomable Image Annotation

IMMARKUS provides a zoomable view to support annotating large images, and tools for creating __rectangle__, __polygon__ and __circle/ellipse__ selections. Similar to multi-image viewers like [Mirador](https://projectmirador.org/), IMMARKUS provides a multi-window environment for annotating multiple images side by side.

<img width="1427" alt="Screenshot 2024-03-04 at 11 40 09" src="update-images/01_overview_fig1.png">

**Figure 1.** Multi-Window Zoomable Image Annotation in IMMARKUS

* Read more about [Annotating Multiple Images Simultaneously](https://github.com/rsimon/immarkus/wiki/05-Annotating-Images#annotating-multiple-images-simultaneously)

## Design Your Own Data Model

IMMARKUS includes a form-based editor for creating and managing your personal data model. The data model is designed around the concepts of **Entity Classes** and **Properties**.

- Use __Entity Classes__ to annotate classes of concepts or things (e.g., a city wall, a bridge, a human figure, an animal, a plant).
- Define __Properties__ for your Entity Classes, to record specific details about entity classes (e.g., name, dimension, location, identifier). 
- Your data model can be __hierarchical__. Each entity class can have a parent class. Properties of the parent class are automatically inherited by the child class. This allows you to define common properties that are shared between parent and child entity classes, as well as properties that are particular to child classes.

<img width="958" alt="Screenshot 2024-03-04 at 13 11 01" src="https://github.com/rsimon/immarkus/assets/160752064/b8d54fa9-53dc-414e-b291-d62f46b76a9b">

**Figure 2.** Defining Entities in IMMARKUS


* Read more about [Designing a Data Model](https://github.com/rsimon/immarkus/wiki/04-Designing-a-Data-Model)

## Property Types

IMMARKUS offers a range of data types you can use to capture properties of different entity classes. Think of it as a personal "database builder" for your data model. The following seven data types are currently available:

- Text 
- Number
- Options
- URI
- Geo-coordinates
- Measurement 
- External Authority 

<img width="978" alt="Screenshot 2024-03-04 at 11 45 01" src="https://github.com/rsimon/immarkus/assets/160752064/996cd609-c1c3-4a96-b51c-f7ee376e3a7a">

**Figure 3.** Defining Properties in IMMARKUS

* Read more about [Property Options](https://github.com/rsimon/immarkus/wiki/04-Designing-a-Data-Model#property-options)