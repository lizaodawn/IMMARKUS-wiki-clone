In IMMARKUS, the data model is based on the concepts of entity classes and properties. In short, we use **entity classes** to annotate specific concepts or things (e.g., a city wall); and we use **properties** to record specific details about entity classes (e.g., the name, dimension, and location). You can create and view entities and properties both in the Annotation mode and in the Data Model.

In the **hierarchical data model**, we can define common properties that are shared between parent and child entity classes. Child classes inherit properties from parent classes. We can also define properties that are specific to child classes.




# Creating Entities and Properties in Annotation Mode

To create entities, in the image gallery, click the subfolder containing the images you want to work with. This will open the images in the folder.

1. In the Image Gallery, decide which part of the image you would like to tag and draw a shape. 
After you have drawn a shape, you will see the Add Tag and Add Note buttons in the sidebar on the right. 
Choose **Add Tag** and it will open a popup window like one shown in **figure 5**. 

![image](https://github.com/rsimon/immarkus/assets/160752064/991ed294-0206-4a91-ae48-a9316b481981)



2.	Click **Create New Entity Class**. 



![Screenshot (487)](https://github.com/rsimon/immarkus/assets/128056738/e9d557b0-6af3-41a8-8a3d-5e7fadadfccc)

**Figure 5.** Create Entities in Annotation Mode

3.	Click on **Entity Class** and name the entity class (e.g. "city_gate.”)

    •	You can select the color of each entity on the right panel.
4.	You can define a different **Display Name**. In this case, "city gate.”
5.	Add an **Entity Class Description** that explains how to use this entity class (e.g., instances of city gates in the image).  
6.	Add/edit the properties. Click the drop down menu next to **No Properties** (the blue arrow in **figure 6**)

![Screenshot (488)](https://github.com/rsimon/immarkus/assets/128056738/74052980-2bf6-4b82-884a-3130bdd2a721)

**Figure 6.** Create Entities and Properties

7.	Click **Add Property**. This opens the property editor as shown in **figure 7**.

![Screenshot (489)](https://github.com/rsimon/immarkus/assets/128056738/915a5228-ae1e-4067-8c40-787f4c81e797)

**Figure 7.** Add Properties

8.	Add a property. Define **Property Name**.

9.	Now select a data type by clicking the drop-down menu under **Data Type**. You can select as many properties as you need to create a schema for your entity class. The following seven data types are currently available:

     •	**Text** - a basic text field

     •	**Number** - a numeric field

     •	**Options** - a list of values to choose from

     •	**URI** - a text field which validates whether the content is a URI, and which will be clickable in the interface

     •	**Geo-Coordinates** - a latitude/longitude coordinate pair

     •	**Measurement** – a number combined with a measurement word

     •	**[External Authority](https://github.com/rsimon/immarkus/wiki/t_04-Annotation-Mode#add-external-authorities)** (follow the link)

10.	The data type of "name" is **Text**. You can also add a description of the property in **Property Description**.

![Screenshot (490)](https://github.com/rsimon/immarkus/assets/128056738/a59a9c46-0a07-4db2-bf2b-b5d8161ee79f)

**Figure 8.** Choose Data Type


11.	After you have added each property, click **Save Property**. 

12.	When you are finished adding properties, click **Save Entity Class**.

## Add External Authorities

Using the External Authority property type allows you to associate an entity class with one or more external authority services. You can add multiple authorities per field, and multiple fields per entity class. 
In the property editor, type a name for your property ("place ID" in **figure 9**) and select the External Authority field type.

![Screenshot (491)](https://github.com/rsimon/immarkus/assets/128056738/8b581e78-bb41-42d5-9664-ebae050103b4)

**Figure 9.** External Authorities

As you fill in properties for the annotated entity, the external authority popup displays a search field and the authority service result page below it.  Click the ↗ icon on the right side of the search field to open the current authority search in a new browser tab. The links to external authorities need to be copy-and-pasted in the relevant field of the schema.

![Screenshot (494)](https://github.com/rsimon/immarkus/assets/128056738/cbaf8a8d-f7f1-4c35-b1c0-d40803e49cd3)

**Figure 10.** Wikipedia Search Result of "Yangzhou" Using IMMARKUS

# Annotate Multiple Images on the Same Screen

You can annotate images side by side by clicking **Add Image**. In this mode, you can annotate multiple images at the same time. You can drag and drop windows to move them around and change their layout.

![Picture11](https://github.com/rsimon/immarkus/assets/128056738/18df8963-93a5-4304-be1b-819c85a2729d)

**Figure 11.** Annotate Multiple Images Using Add Image

You can create a child class in annotation mode (see **figure 12**) and in the Data Model. Click the Create New Entity button and: 

1. Define **Entity Class** (city_gate) 

1. Define **Display Name** (City gate) 

1. Choose the **Parent Class** (in this case the Parent is obj_part) 

![Screenshot (495)](https://github.com/rsimon/immarkus/assets/128056738/68f14260-31e9-4a0b-99e0-93b6fe0a7586)


**Figure 12.** Create Child- Parent Relationships
<br/><br/>

## Inherited Properties

In **figure 13**, the child class named "city_gate" inherits all the properties from the parent class named "obj_part".  

In the Properties editor, it looks like this entity does not have any properties (circled in red in **figure 13**). This means no specific property has been added to this child class. The child class city_gate inherited all the properties from its parent class (circled in blue) as shown on the right sidebar in **figure 13**.


![Screenshot (496)](https://github.com/rsimon/immarkus/assets/128056738/fa26f2c4-4600-4f84-9fa7-017c3bf454ff)

**Figure 13.**  The Child Class "city gate" Inherits Properties from its Parent Class "obj_part" 
<br/><br/>

## View Parent-Child Relationship

Classes do not need to have a parent-child relationship. Whether they do depends on your own data design. 

The entity classes for which you have created child classes have a drop-down menu (“>”) on the left (red square in **figure 14**). 

* Click the drop-down menu to expand the parent class and you will see child classes belonging to the parent class.  

* The properties belonging to or inherited from the parent to the child class are shown on the row of the parent class.  

* On the row of the child class, you can only see the properties specifically added to the child class (see the properties for "location site" parent and "survey area" child on **figure 14**). 

Classes that do not have children have no drop-down menu (blue square on **figure 14**).  

![Screenshot (82)](https://github.com/rsimon/immarkus/assets/128056738/7a9f5b76-79c2-4d3f-bf3c-61f41f87dad9)

**Figure 14.** Entity Classes in the Data Model
<br/><br/>

# Creating Metadata Schemas


You can also create metadata schemas in the Data Model view. The metadata can be recorded at the folder (or sub-folder) level as well as at the individual image level. 

## Adding Folder Metadata

1. Go to the **Folder Metadata** tab and click **New Folder Schema**. 

![Screenshot (498)](https://github.com/rsimon/immarkus/assets/128056738/2210a06d-eedd-482f-b519-16b28e845113)

**Figure 15. Folder Metadata** 
<br/><br/>

2.  Metadata properties are added in the same way as entity classes, with the same [property options](https://github.com/rsimon/immarkus/wiki/t_04-Annotation-Mode#creating-entities-and-properties-in-annotation-mode).  

![Screenshot (499)](https://github.com/rsimon/immarkus/assets/128056738/3ec44d69-8f94-4085-af65-05b2677f9879)

**Figure 16.** Add Folder Metadata
<br/><br/>

3. Add **Property Name** ("title” below) and choose a **Data Type** ("text"). Click **Save Property**. 

![Screenshot (500)](https://github.com/rsimon/immarkus/assets/128056738/b4d6c9f2-2c97-4e69-b3d6-f6109c744b89)

**Figure 17.** Choose Data Type of Folder Metadata

4. Be sure to click **Save Schema** after you are done adding properties.
