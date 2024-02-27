# Creating a Hierarchical Data Model
You can create a hierarchical data model. For the concepts of entities and properties see __t_04_03 (link needed)__ 
<br/><br/><br/>

## Parent-Child Entity Classes 

 



In the data model, we can define common properties that are shared among parent and child entity classes. Child classes inherit properties from parent classes. Also, we can define properties that are specific to child classes.  

You can create a child class in annotation mode and in the Data Model __(see figure 12)__. Click the Create New Entity button and: 

1. Define **Entity Class** (city_gate) 

1. Define **Display Name** (city gate) 

1. Choose the **Parent Class** (in this case the Parent is obj_part.) 

<img width="651" alt="Bildschirmfoto 2024-01-09 um 12 21 57" src="https://github.com/sunkyulee22/asset/assets/160752064/ac5361a3-d350-45fb-96f6-eba7664fe221)">
<br/>

**Figure 12. Create Entity on Data Model**
<br/><br/>

## Inherited Properties

In Figure 13, the child class named "city_gate" inherits all the properties from the parent class named "obj_part".  

In the Properties editor, it looks like this entity does not have any properties (circled in blue in **figure 13**). This means no specific property has been added to this child class. But as a child class city_gate inherits all the properties from the parent class (as shown on the right sidebar in **figure 13**).

<img width="651" alt="Bildschirmfoto 2024-01-09 um 12 21 57" src="https://github.com/sunkyulee22/asset/assets/160752064/1ba17ef9-e3b5-471f-ac42-15bc23c96e37"> 
<br/>

**Figure 13. A child class properties inherited from a parent class** 

<br/><br/><br/>

## View Parent-Child Relationship

Classes do not need to have a parent-child relationship. Whether they do depends on your own data design. 

* The entity classes for which you have created child classes have a drop-down menu “>” on the left (red square in **figure 14**). 

> * Click the drop-down menu to expand the parent class and you will see child classes belonging to the parent class.  

> * The properties belonging to or inherited from the parent to the child class are shown on the row of the parent class.  

> * On the row of the child class, you can only see the properties specifically added to the child class. 

* The ones that do not have children have no drop-down menu (blue square in **figure 14**).  

<img width="651" alt="Bildschirmfoto 2024-01-09 um 12 21 57" src="https://github.com/sunkyulee22/asset/assets/160752064/d74b60d6-8a84-4312-975f-498fb7c8c571">
<br/>

**Figure 14. Entity Classes on Data Model**


