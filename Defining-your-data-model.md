Before you start working with IMMARKUS, you have to define a data model. The data model has three parts:

- The __Image Metadata__ schema, which defines how you describe the __image files__ in your collection.
- The __Folder Metadata__ schema, which defines how you record information about the __directory folders__ in your collection. This can be useful in case your folders represent sub-collections.
- Most importantly: the __Entity Class model__, which defines the classes you will use to identify Entities in you image annotations.

<img width="1000" alt="Bildschirmfoto 2024-01-10 um 13 30 59" src="https://github.com/rsimon/immarkus/assets/470971/633cd951-117f-40a1-b241-0dea59dffed0">

## Entity Classes

Click the __Create Entity Class__ button to create a new class. This will open the Entity Class editor.

<img width="800" alt="Bildschirmfoto 2024-01-10 um 13 38 51" src="https://github.com/rsimon/immarkus/assets/470971/93cd7bc3-4d32-4e8a-9bdb-aedc61ed6f3c">

- Choose a __unique identifier__ for the class (mandatory)
- Pick a __color__ (this will be for color-coding image annotations later)

Optionally:
- Choose a user-friendly __display name__ for your class
- Pick a __parent entity class__, in case your data model is hierarchical (more below)
- Add a __description__ that explains how to use this entity class

On the right side of the editor, you will see a preview of how your Entity Class will appear, when used in the annotation interface.

## Entity Class Properties

The purpose of Entity Classes is not just to identify certain things or concepts in your annotations. They also allow you to record specific details of an entity in a structured manner.