# Creating Entities and Properties in Annotation Mode

After you have finished drawing, you will see the Add Tag and Add Note buttons in the sidebar on the right. Choose **Add Tag** and it will open a popup window like one shown in **figure 5**. 

In IMMARKUS, the data model is based on the concepts of entity classes and properties. In short, we use **entity classes** to annotate specific concepts or things (e.g., a city wall); and we use **properties** to record specific details about entity classes (e.g., the name, dimension, and location).
You can create and view entities and properties in the Annotation mode. First, we will create entities.

1.	Click **Create New Entity Class**. 

![Screenshot (487)](https://github.com/rsimon/immarkus/assets/128056738/e9d557b0-6af3-41a8-8a3d-5e7fadadfccc)


**Figure 5.** Create Entities in Annotation Mode

2.	Click new **entity class** and name the entity class (e.g. "city_gate.”)

    •	You can choose the color of each entity on the right panel.
3.	You can choose a different **display name**. In this case, "city gate.”
4.	Add an **entity class description** that explains how to use this entity class (e.g., instances of city gates in the image).  
5.	Add/edit the properties. Click the drop down menu next to **No Properties** (the blue arrow in **figure 6**)

![Screenshot (488)](https://github.com/rsimon/immarkus/assets/128056738/74052980-2bf6-4b82-884a-3130bdd2a721)

**Figure 6.** Create Entities and Properties

6.	Click **Add Property**. This opens the property editor as shown in **figure 7**.

![Screenshot (489)](https://github.com/rsimon/immarkus/assets/128056738/915a5228-ae1e-4067-8c40-787f4c81e797)

**Figure 7.** Add Properties

7.	Add a property. Define **Property Name**.

8.	Now choose a data type by clicking the drop-down menu under **Data Type**. Here you can select however many properties to create a schema for your entity class. The following seven data types are currently available:

     •	**Text** - a basic text field

     •	**Number** - a numeric field

     •	**Options** - a list of values to choose from

     •	**URI** - a text field which validates whether the content is a URI, and which will be clickable in the interface

     •	**Geo-Coordinates** - a latitude/longitude coordinate pair

     •	**Measurement** – a number combined with a measurement word

     •	**External Authority** (see below on ädd external authorities)

9.	Since the data type of "name" is text, I choose Text. You can also add a description of the property in **Property Description**.

![Screenshot (490)](https://github.com/rsimon/immarkus/assets/128056738/a59a9c46-0a07-4db2-bf2b-b5d8161ee79f)

**Figure 8.** Choose Data Type


10.	After you have added each property, click **Save Property**. 

11.	After you are done adding properties, click **Save Entity Class**.