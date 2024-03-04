In IMMARKUS you can define a data model consisting of entity classes and properties. A well-designed data model can help ensure that you gather data systematically and tailored to the research questions the annotation process is aimed to address. Data models can also help ensure consistency in collaborative research projects.

**Entity classes** are used to annotate classes of concepts or things (e.g., a city wall, a bridge, a human figure, an animal, a plant); **properties** can be used to record specific details about entity classes (e.g., name, dimension, location, identifier). You can create and view entities and properties in both [annotation mode](https://github.com/rsimon/immarkus/wiki/04-Annotating-Images) and data model mode. 

In the IMMARKUS **hierarchical data model**, you can define common properties that are shared between parent and child entity classes. Child classes inherit properties from parent classes. We can also define properties that are specific to child classes.

# Creating Entities and Properties in the Data Model Mode

To create entities and properties in the data model mode, enter the data model mode by clicking Data Model on your left side bar.

1. On the upper menu bar you will see that you are editing Entity Classes. Click **Create New Entity Class**.

![Screenshot (540)](https://github.com/rsimon/immarkus/assets/128056738/b062b31e-9e57-4e15-bfc6-ffead8aef613)

**Figure 6**. Creating Entities in the Data Model Mode

2. Click **Entity Class** and name the entity class (e.g. "bridge”).

    •	You can select the color of each entity on the right panel.

6.	You can define a different **Display Name**. Or you can leave it empty to display the same entity class name (e.g. "bridge")
7.	Add an **Entity Class Description** that explains the use of this entity class (e.g., "a bridge is an elevated structure across a river or other obstacles")

8.	Add/edit the properties. Click the drop down menu next to **No Properties** (circled in blue in **Figure 7**)

<img width="952" alt="Screenshot 2024-03-02 at 23 47 22" src="https://github.com/rsimon/immarkus/assets/160752064/1f2811c5-73c9-48ce-9a51-9816c39fb390">

**Figure 7.** Creating Properties in the Data Model Mode

9.	Click **Add Property**. This opens the property editor as shown in **Figure 8**.

<img width="962" alt="Screenshot 2024-03-02 at 23 52 50" src="https://github.com/rsimon/immarkus/assets/160752064/3483cc2c-0fa3-4b5f-857b-323d0c6a9706">

**Figure 8.** Adding Properties in Data Model Mode

10.	Define the **Property Name**.

11.	Select a data type by clicking the drop-down menu under **Data Type**. You can select as many properties as you need to create a schema for your entity class. The following seven data types are currently available:

### Property Options

* **Text** - a basic text field

* **Number** - a numeric field

* **Options** - a list of values to choose from

* **URI** - a text field which validates whether the content is a URI, and which will be clickable in the interface

* **Geo-Coordinates** - a latitude/longitude coordinate pair

* **Measurement** – a number combined with a measurement word

* **[External Authority](https://github.com/rsimon/immarkus/wiki/04-Annotating-Images#using-external-authorities-in-annotations)** - external authority services such as TGAZ, CBDB, and Wikipedia.


12.	The data type of "id" is **Text**. You can also add a description of the property in **Property Description**.

<img width="953" alt="Screenshot 2024-03-02 at 23 57 34" src="https://github.com/rsimon/immarkus/assets/160752064/fdbe477b-3e09-479d-b048-57bd38f72c1d">


**Figure 9.** Selecting a Data Type in the Data Model Mode


13.	After you have added each property, click **Save Property**. 

14.	When you have finished adding properties, click **Save Entity Class**.




	 

# Creating Parent-Child Entity Classes in the Data Model Mode

In the Data Model, you can define common properties that are shared between parent and child entity classes. Child classes inherit properties from parent classes. You can also define properties that are particular to child classes. (If you cannot locate the Data Model mode, see the [The Interface](https://github.com/rsimon/immarkus/wiki/02-The-Interface)) 

You can create a child class in both annotation Mode and data model mode. 

1. Click the **Create New Entity** button 

1. Define **Entity Class** (city_gate) 

1. Define **Display Name** (City gate) 

1. Select the **Parent Class** (in this case the Parent is obj_part) 

![Screenshot (495)](https://github.com/rsimon/immarkus/assets/128056738/68f14260-31e9-4a0b-99e0-93b6fe0a7586)


**Figure 10.** Creating Parent-Child Relationships
<br/><br/>

## Inherited Properties

In **Figure 10 and 11**, the child class named "city_gate" inherits all the properties from the parent class named "obj_part".  

In the Properties editor, it looks like this entity does not have any properties (circled in red in **Figure 11**). This means no particular property has been added to this child class. The child class city_gate inherited all the properties from its parent class (circled in blue) as shown on the right panel in **Figure 11**.


![Screenshot (496)](https://github.com/rsimon/immarkus/assets/128056738/fa26f2c4-4600-4f84-9fa7-017c3bf454ff)

**Figure 11.**  The Child Class "city gate" Inherits Properties from its Parent Class "obj_part" 
<br/><br/>

## Viewing Parent-Child Relationships

Classes do not need to have a parent-child relationship. Whether they do depends on your own data design. 

The entity classes for which you have created child classes have a drop-down menu (“>”) on the left (red square in **Figure 12**). 

* Click the drop-down menu to expand the parent class and you will see child classes belonging to the parent class.  

* The properties belonging to or inherited from the parent to the child class are shown in the row for the parent class.  

* In the row of the child class, you can only see the properties that have been specifically added to the child class (see the properties for "location_site" parent and "survey area" child in **Figure 12**). 

Classes that have no children do not have a drop-down menu (blue square in **Figure 10**).  


![Screenshot (519)](https://github.com/rsimon/immarkus/assets/128056738/9fd1e53f-8c56-4782-81b8-bc62df540365)

**Figure 12.** Entity Classes in the Data Model

<br/><br/>
