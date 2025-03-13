The **Knowledge Graph** (**Figure 1**) organizes data from all sources (folders and images) and allows you to view and query these sources, all data and metadata annotations, and the relations you established between them. You can also navigate to the desired content from the knowledge graph, and export your search results.   

# Default View 

## Nodes and Edges in the Graph

The default view shows all images (blue nodes) and entity classes (green nodes). Edges between images and annotations are shown as blue lines, with the weight indicating the number of connections. Edges representing parent-child relationships between entity classes in your data model are shown as green dashed lines.

To add subfolders as nodes to the default view, see [Show Subfolders as Nodes](https://github.com/rsimon/immarkus/wiki/07-Exploring-Data-in-Knowledge-Graph#show-subfolders-as-nodes). 

Use the scroll wheel on your mouse to **zoom** in and out of the knowledge graph. To **pan** the graph across the screen, click on an empty space on the graph and drag your cursor across the screen. 

![07_exploring-data-in-knowledge-graph_fig1](https://github.com/user-attachments/assets/7880de05-3187-48d8-9d99-f7ae121374d9)  
**Figure 1.** Default View of Knowledge Graph 

Hovering over a node highlights its related nodes and edges. When hovering over an annotation edge, a tooltip displays the number of annotations connected to the corresponding image.

![07_exploring-data-in-knowledge-graph_fig2](https://github.com/user-attachments/assets/44dd0327-0c59-4071-98b5-ab2bd050b524)  
**Figure 2.** Highlighting Connections by Hovering Over the Node "platform"

![07_exploring-data-in-knowledge-graph_fig3](https://github.com/user-attachments/assets/75c7a0a0-089a-449a-8054-db266a68378c)  
**Figure 3.** Tooltip Displaying the Number of Annotations Linked to an Image

## View Options and Controls

* **Legend Panel**:  Displays a guide to what each node and edge represents in the graph.  

    ![07_exploring-data-in-knowledge-graph_fig4](https://github.com/user-attachments/assets/d6df87ff-e341-485d-b2f3-7582248ce80d)  
    **Figure 4.** Legend Panel in the Knowledge Graph

* **Full Screen Expander**: Click the **expand** button (outlined in blue in **Figure 5**) to view the graph in full-screen mode.  

    ![07_exploring-data-in-knowledge-graph_fig5](https://github.com/user-attachments/assets/817acbc8-d850-4b6c-84a4-040a4791f0c7)  
    **Figure 5.** Viewing the Knowledge Graph in Full-screen Mode  

* **Graph Searcher**: Click the **magnify glass** (outlined in blue in **Figure 6**) icon to open the graph search dialog box and enter search conditions. See [Knowledge Graph Search](07-Exploring-Data-in-Knowledge-Graph#knowledge-graph-search) for more more details on graph search and export.

    ![07_exploring-data-in-knowledge-graph_fig6](https://github.com/user-attachments/assets/4c773fc6-c0ea-46d2-9773-7c7400632a5e)  
    **Figure 6** Opening the Graph Search Dialog Box

* **Settings**: Click the **Settings** button to customize the knowledge graph view (see [Settings](https://github.com/rsimon/immarkus/wiki/07-Exploring-Data-in-Knowledge-Graph#settings)). 
    
    ![07_exploring-data-in-knowledge-graph_fig7](https://github.com/user-attachments/assets/5aa2db5f-1e14-4420-a58b-dd6ea6375469)  
    **Figure 7** Adjusting the Knowledge Graph View in the Settings Panel 

* **Details Panel**: Clicking on a node expands a panel on the right, allowing you to explore related annotations, images, relations, and metadata. You can also navigate to the image **Annotation Mode** from here.

    ![07_exploring-data-in-knowledge-graph_fig8](https://github.com/user-attachments/assets/5af8d974-4768-43e1-a50b-ddf40bf9066d)  
    **Figure 8** Navigating Details Panel for the Seleted Entity Class "city_wall"


# Settings 

From Settings you can change the way the data is displayed. Clicking on the **Settings** icon on the bottom right corner of the knowledge graph will take you to a menu with several options. You can combine selections from those options to adapt the graph to your needs.  

## Choose Graph Type

You can choose to visualize your data in **Hierarchy & Annotations** mode, which shows the data model structure and entity annotations, or in **Relationships** mode, which shows the relationship annotations you created between entity classes. 

![07_exploring-data-in-knowledge-graph_fig9](https://github.com/user-attachments/assets/3887953f-1a62-4dfa-a5c8-c2f1418adb6f)  
**Figure 9.** Choosing **Hierarchy & Annotations** Mode for the Knowledge Graph


## Hide Labels 

**Hide labels** hides text labels from the graph. You can further choose to only hide **Image** labels or **Entity Class** lables. You can view the labels by hovering over nodes (**Figure 10**). 

![07_exploring-data-in-knowledge-graph_fig10](https://github.com/user-attachments/assets/bd7f896b-6a12-4542-b238-de6bd42610cc)  
**Figure 10.** Hiding Image Labels in the Knowledge Graph with the Label *康熙_隰州志_30.png* Made Visible by Hovering over the Node 

## Show Subfolders as Nodes  

**Show subfolders as nodes** allows you to see the distribution of your images and entities across subfolders on the graph (crimson nodes on **Figure 11**)
 
![07_exploring-data-in-knowledge-graph_fig11](https://github.com/user-attachments/assets/c368d922-585a-4047-90ca-85092783a54d)  
**Figure 11.** Showing Subfolders as Nodes  

## Hide Unconnected Nodes  

**Hide unconnected nodes** hides unused entity classes and images without entity annotations and makes the graph less cluttered and focused on annotated content. 

![07_exploring-data-in-knowledge-graph_fig12a](https://github.com/user-attachments/assets/d105d9d8-b2b2-469f-a892-c285df58a9a1)  
**Figure 12a.** Before Selecting "Hide unconnected nodes": Image Nodes without Annotations Displayed as Unconnected Nodes in the Graph

![07_exploring-data-in-knowledge-graph_fig12b](https://github.com/user-attachments/assets/870ebd99-eb99-4dd7-a0d5-8cc48a1ab9bc)  
**Figure 12b.** After Selecting "Hide unconnected nodes": Image Nodes without Annotations are Hidden from the Graph

# Nodes
You can inspect individual nodes, move them, and pin them on the knowledge graph (**Figure 13**).  Click and drag a node to pin it on the knowledge graph. To unpin a node, click on the pin icon at the bottom of the screen (outlined in blue). 

![07_exploring-data-in-knowledge-graph_fig13](https://github.com/user-attachments/assets/c3dfb36b-2845-4adc-a5ea-f7b3a0c5eef3)  
**Figure 13.** Pinning the Node "tower" on the Knowledge Graph 


## Entity Class Nodes 

To see all annotations of a specific entity class click on an entity class node (in this case _tower_) (**Figure 14**). You can see an overview of the related annotations and relationships for this entity class. You can access the individual annotations by clicking on the **open image icon** (outlined in **Figure 14**). IMMARKUS will then take you to the individual image in the [Image Gallery](https://github.com/rsimon/immarkus/wiki/03-The-Interface). When you return to the Knowledge Graph, the browser memory will have retained the selected view and node.

![07_exploring-data-in-knowledge-graph_fig14](https://github.com/user-attachments/assets/b3d94dc3-8f58-4b6b-a706-1f32cddd8bc0)  
**Figure 14.** Clicking on an Individual Entity Class to Select it


## Image Nodes 

If you want to see all entity classes and relationships annotated on an individual image, click on an image node (**Figure 15**). You can access the image by clicking on the **open image icon** (outlined in **Figure 15**). IMMARKUS will then take you to the individual image in the [Image Gallery](https://github.com/rsimon/immarkus/wiki/03-The-Interface). When you return to the Knowledge Graph, the browser memory will have retained the selected view and node. 

![07_exploring-data-in-knowledge-graph_fig15](https://github.com/user-attachments/assets/2f4a4897-c60b-4a59-9083-85ae4f27609b)  
**Figure 15.** Clicking on an Individual Image Node in the Knowledge Graph to Select it  

To view and modify image metadata in the **Knowledge Graph** view, select an image node and click on the **Metadata** button (outlined in blue).  From here you can also select a predefined schema and fill out image metadata (**Figure 16**). 

![07_exploring-data-in-knowledge-graph_fig16](https://github.com/user-attachments/assets/868d3e08-6159-4cf9-a942-7ab85eca5560)  
**Figure 16.** Viewing and Modifying Image Metadata in the Knowledge Graph 


## Subfolder Nodes 

By clicking a subfolder node, you can view the total number of images in the folder and access its metadata. To navigate to the subfolder, click the **Open** button (outlined in blue). When you return to the Knowledge Graph page, the browser memory will retain the selected node. 
 
![07_exploring-data-in-knowledge-graph_fig17](https://github.com/user-attachments/assets/5ebda448-5759-462a-a1e7-483e91923496)  
**Figure 17.** Selecting a Subfolder Node to View Its Metadata 

To deselect a node in order to explore other nodes, click any where outside the selection or close the right panel.

# Knowledge Graph Search 

In **Graph Search** you can search and filter images in the current project according to metadata and/or properties; you can also export the results of your search.  

Start searching by clicking the magnifying glass icon (outlined in blue on **Figure 18**). 

In **Hierarchy & Annotations** you can search either subfolders by metadata, or images by (image or subfolder) metadata, entity classes, or notes. 

In **Relationships mode**, you can search entity classes or images by the relationships that were added in annotation. 

You can further explore the search results by selecting individual nodes to view image or node data and/or by hovering over nodes to view the nodes to which they are related.

![07_exploring-data-in-knowledge-graph_fig18a](https://github.com/user-attachments/assets/a9ffa033-9081-4951-972a-5d7e5bcc5826)  
**Figure 18a.** Searching Images with *bridge* Entities in Graph Search

![07_exploring-data-in-knowledge-graph_fig18b](https://github.com/user-attachments/assets/1afd300c-012d-419d-bdaa-2bc237a67230)  
**Figure 18b.** Hovering over an Image Node in the Search Results for Images with *bridge* Entities


## Graph Search Options

In the **Graph Search** dialog box, you can define conditions or combinations of conditions to query metadata, annotations, and their relationships within the knowledge graph.

### Basic Search
* Hireachy & Annotations Mode
  - Search for **Subfolders** by metadata
  - Search for **Images** by metadata
  - Search for **Images** by annotated entity or note

* Relationships Mode
  - Search for **Entity Classes** by relationship
  - Search for **Images** by relationship

### Adding and Managing Conditions
* Click **Add Condition** to add an and/or condition to your search. 
* Click **Sub-Condition** to further filter on properties of an entity class. 
* Edit your search by either deleting individual conditions or sub-conditions. 
* Reset the search by pressing the **Clear All button**. 

## Export Graph Search Result

Click **Export Search Result** to export the results of your search to an .XLSX file. 


![07_exploring-data-in-knowledge-graph_fig19](https://github.com/user-attachments/assets/b57e3d9d-1cca-4284-a7ca-a8afe4a15dae)  
**Figure 19** Exporting Query Results of Annotated Relationships from the Knowledge Graph

![07_exploring-data-in-knowledge-graph_fig20](https://github.com/user-attachments/assets/bf7c792c-f0e6-4431-ae8d-6ad392da59c2)  
**Figure 20** Exporting Annotations, Relationships, and Full Metadata from an Image Search in the Knowledge Graph



