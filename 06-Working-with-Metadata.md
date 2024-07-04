# Creating a Metadata Schema

You can create a metadata schema in the **Data Model** view. You can record metadata at the folder (or subfolder) level as well as at the individual image level. 
- The [Image Metadata Schema ](https://github.com/rsimon/immarkus/wiki/06-Working-with-Metadata#adding-a-metadata-schema-for-individual-images) defines how you describe individual __image files__ in your collection.
- The [Folder Metadata Schema](https://github.com/rsimon/immarkus/wiki/06-Working-with-Metadata#adding-a-folder-metadata-schema) defines how you record information about the __directory folders__ in your collection. This can be useful if your folder contains images from the same book, artwork, or publication, so that you do not have to enter in the same metadata information for each individual image in the subfolder.

## Adding a Folder Metadata Schema

1. In the **Data Model** view, go to the **Folder Metadata** tab and click **New Folder Schema**. 

<img width="1189" alt="Screenshot 2024-03-03 at 01 02 00" src="https://github.com/rsimon/immarkus/assets/160752064/f49ff713-296c-4ce9-8bd5-d4dff7c76882">


**Figure 1**. Examples of Folder Metadata Schemas
<br/><br/>

2.  Metadata categories are added in the same way as properties for entity classes with similar [property options](https://github.com/rsimon/immarkus/wiki/04-Designing-a-Data-Model#property-options).  

<img width="837" alt="Screenshot 2024-03-03 at 00 39 13" src="https://github.com/rsimon/immarkus/assets/160752064/2e5a7224-4522-412d-bced-84a3339a2852">


**Figure 2.** Adding a Schema for Folder Metadata
<br/><br/>

3. Add a metadata field under **Property Name** ("author_cbdb_id”) and choose a **Data Type** ("External Authority"-choose at least one external authority, such as CBDB). Click **Save Property**. 

![image](https://github.com/rsimon/immarkus/assets/160752064/176eef10-9fed-40d0-a389-8e6fd8467c92)


**Figure 3.** Setting a Data Type in a Folder Metadata Schema

4. Be sure to click **Save Schema** after you are done adding properties.

![image](https://github.com/rsimon/immarkus/assets/160752064/d5aee4f8-e1e1-45ae-9eaf-59697121c520)


**Figure 4.** Saving a Folder Metadata Schema

## Adding a Metadata Schema for Individual Images

A metadata schema for individual images can be added in the same way as metadata schemas for folders.  

1. Choose **Image Metadata** and click **New Image Schema**. 

<img width="917" alt="Screenshot 2024-03-03 at 01 21 41" src="https://github.com/rsimon/immarkus/assets/160752064/faf265e2-0fc3-4a05-b4e9-864496725378">

**Figure 5.**  Creating a Metadata Schema for Individual Images
<br/><br/>
2. Define **Property Name** and choose **Data Type**. Click **Save Property**. 

<img width="819" alt="Screenshot 2024-03-03 at 01 25 49" src="https://github.com/rsimon/immarkus/assets/160752064/af4a0c0d-1b18-4645-80a3-2c8693ba4af5">


**Figure 6.** Setting a Data Type in a Metadata Schema for Individual Images
<br/><br/>

# Importing Data Models for Metadata


## Importing an Image Metadata Model 
To import an image metadata model click **Import Model** under **Image Metadata** (**Figure 7**).

![import image metadata 1](https://github.com/rsimon/immarkus/assets/128056738/f53e5349-f5d4-4ad9-b9ad-da8c118289d6)

**Figure 7**. Importing a Model for Image Metadata

From the pop-up window you can upload an image metadata model (**Figure 8**) or replace the current schema. You can also indicate how duplicates should be handled (**Figure 9**).

![import image metadata 2](https://github.com/rsimon/immarkus/assets/128056738/b73c9d81-0bc9-4f48-a28c-5a098253d15f)

**Figure 8.** Importing a Metadata Model  


![import image metadata 3](https://github.com/rsimon/immarkus/assets/128056738/6456252f-9b7d-40a9-8d29-f27c4e608eb4)

**Figure 9.** Handling Duplicate Classes during Import



When importing an image metadata model, you can choose to import from preset image metadata models (in blue on **Figure 10**) which include schemas for ‘archaeological image’, ‘artwork’, and ‘historical printed illustration’ or you can click **Upload Datamodel File** to upload your own data model.


![image import preset](https://github.com/rsimon/immarkus/assets/128056738/a3418aea-cf71-4180-9602-132aa9b87f38)


**Figure 10.** Importing Predefined Image  Metadata Models

## Importing a Folder Metadata Model

To import a folder metadata model, click the **Import Model** button under **Folder Metadata** (in blue on **Figure 11**).


![folder import 1](https://github.com/rsimon/immarkus/assets/128056738/c0d40f73-2771-4390-b376-45e07ba6fce2)

**Figure 11.** Importing a Model for Folder Metadata

The pop-up is identical to the one in **Image Metadata** (**Figures 8** and **9**) and you can select from the same options. The preset options include ‘artwork’, ‘historical printed text’, ‘journal article’, and ‘modern monograph’  (**Figure 12**).



![folder import 2](https://github.com/rsimon/immarkus/assets/128056738/1b5364b2-b7c6-4584-b4bc-656da1bcc72e)

**Figure 12.** Importing a Preset Folder Metadata Model

# Recording Metadata

After defining your metadata schemas, you can enter metadata for folders and images in the Image Gallery. You can also enter image metadata in the Annotation Mode (but not folder metadata).

## Recording Folder Metadata in the Image Gallery 

1. Click **Images** on the left sidebar to move to the Image Gallery. Click the three dots at the bottom right of the folder and select **Information**.

1. Select a schema for your metadata on the right panel and enter the metadata for the selected folder. After you are done, be sure to click **Save Metadata**. 

![Screenshot (529)](https://github.com/rsimon/immarkus/assets/128056738/acb11fe8-c8d3-4ea8-918f-90e88594f4b9)

**Figure 13**. Recording Folder Metadata in the Image Gallery
<br/>

## Recording Individual Image Metadata in the Image Gallery 
1. Click the three dots on the individual image. 
2. Select a schema for your metadata and fill in the properties in the same way as for the [folder metadata](https://github.com/rsimon/immarkus/wiki/06-Working-with-Metadata#recording-folder-metadata-in-the-image-gallery).

![Screenshot (533)](https://github.com/rsimon/immarkus/assets/128056738/6fe34242-8b76-4a4d-a6f1-8c863e3d12c6)

**Figure 14.** Recording Image Metadata in the Image Gallery   
<br/>

## Recording Metadata in Annotation Mode

You can also enter metadata for individual images in the Annotation Mode. Click the individual image to enter the Annotation Mode and select the metadata tab in the right panel (red square in **Figure 15**). Select the schema for your metadata and fill in the properties you defined under metadata in the Data Model view. 

![Screenshot (537)](https://github.com/rsimon/immarkus/assets/128056738/f0d2ffec-2310-4266-a4e8-eba572fddb04)

**Figure 15.** Recording Image Metadata in the Annotation Mode


