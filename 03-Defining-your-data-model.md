Before you start working with IMMARKUS, you should define a data model. The data model has three parts:

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

## Properties

The purpose of Entity Classes is not just to identify certain things or concepts in your annotations. They also allow you to record specific details about these things or concepts in an efficient way. In order to do this, you can define __Properties__ for your entity class.

- Unfold the __Properties__ section by clicking on it.
- Click __Add Property__. This will open the Property Editor.

<img width="800" alt="Bildschirmfoto 2024-01-10 um 14 09 17" src="https://github.com/rsimon/immarkus/assets/470971/393fd2c7-f13c-400e-ad72-ee8abd87a010">

Think of properties as metadata fields for the entities you will annotate. For example, if you annotate archaological objects, you may want to record their material.

- Enter a __name__ for the property, such as "Material"
- Choose a __data type__ for the property. For example, you may want to pre-define a number of options that you can later choose from in the annotation interface. In this case, select __Options__ as the data type, and the values you want to be available as choices. (Don't worry - you can always edit or add values later.)

Optionally, add a description for the property. (E.g. to clarify what this property is for to other users, in case you plan to share your data model.)

### Property Data Types

The following data types are currently available:

- __Text__ - a basic text field with no particular constraints
- __Number__ - a numeric field
- __Options__ - a list of values to choose from
- __URI__ - a text field which validates whether the content is a URI, and which appear clickable in the interface
- __Geo-Coordinate__ - a latitude/longitude coordinate pair
- __External Authority__ - see our [guide for integrating external authority sources](wiki/Integrating-external-authorities) into your data model

## Data Model Hierarchy

If you data model is hierarchical, Entity Classes will __inherit the properties of their parent classes__. This means you can define common properties, which should be shared among classes, at a root level. Child classes then only need to define properties that are __specific to them.__ This way, you can save time, avoid repetition and stay consistent when defining your data model.

Example:

- Let's assume you define a class called __Geographical Feature__. 
- You define two common properties __Name__ (text) and __Location__ (Geo-Coordinate).
- Next, you define another class called __Terrain__.
- You make __Terrain__ a child concept of __Geographical Feature__.
- You add a new property to __Terrain__ called __Terrain Type__ Option).

<img width="800" alt="Bildschirmfoto 2024-01-10 um 14 28 55" src="https://github.com/rsimon/immarkus/assets/470971/0e6ddc02-9d2e-4b1b-bb3d-fadd87779dde">

As you can see in the preview, __Terrain__ now has three properties: __Name__, __Location__, and __Terrain Type__. The icons next to the __Name__ and __Location__ fields indicate that these are fields inherited from an ancestor class.
