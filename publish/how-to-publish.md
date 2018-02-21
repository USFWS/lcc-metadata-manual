# How to Publish

---

> ![](/assets/best_practice_small.png)Always hit_ refresh_ in your browser before each work session \(and periodically throughout the session\) to ensure you are using the most updated version of mdEditor. Always refresh before you access the publishing menu. However, If you start moving items around in the publishing outline \(see below for details\), you may lose this information once you refresh.
>
> ![](/assets/note_small.png)Currently the  publishing service available through the mdEditor is ScienceBase. In the future, mdEditor will likely be able to work with other databases. Instructions in this manual will use ScienceBase.

---

#### Step One: Logging Into ScienceBase

1. Click the **Publish** button from the top menu in mdEditor.
2. You will be asked to select a _publishing service_. Click on ScienceBase.
3. A login window will appear on the right side of the screen - enter your ScienceBase ID and password, and click **Login**. When you are logged in, the login window will display who you are logged in as. _The current user must have read/write permissions on ScienceBase for any items to be published \(including parent items\)_. You cannot publish until you are logged in.
4. You will see a list of every valid record in mdEditor in the publishing outline with its ScienceBase Identifier \(if the record already exists on ScienceBase\) and its parent ScienceBase Identifier \(if present in the metadata\). This publishing outline shows records in a parent-child relationship and reflects what you would see when you publish in ScienceBase.
5. Records **without parent IDs** already in their metadata will appear directly under the ScienceBase header

   * Indicating that they will be published under the default parent identifier established in the settings. This information is visible on the header, which is hyperlinked to the record on ScienceBase. 

6. Records** that have** **parent IDs** in the metadata record will appear below a thick blue line and will be published under the parent ID in their metadata .

![](/assets/publish_screenshot_2.png)

> ![](/assets/note_small.png) Parent-Child refers to how the records are organized and displayed on ScienceBase; this is different than the Project and Product associations that are embedded within the metadata records.
>
> ![](/assets/note_small.png)If you do not want these parent IDs to change,** do not** drag and drop these records in the publishing outline.

---

#### **How the publishing outline works:**

The publisher looks for the first identifier in a record that matches an existing one in mdEditor and then puts it under that record in the outline. If it doesn't find a matching identifier, it puts the record at the** **root level of the folder that you are uploading to. The root level being the uppermost folder of your organization.

Items directly below the ScienceBase header will be published under the ScienceBase item identified in your settings as “Default Parent Identifier.” Items below the blue line will be published under the parent ID specified in the metadata.

* For example, if the _Default Parent Identifier_ is your LCC Community, then projects at the _root level_ in the publishing outline will be added directly under your LCC Community.

* Products nested under a project in the outline will be added as a direct child item to the project item on ScienceBase.

* Items listed at the root level in the publishing outline don't have a parentID that correspond with a record loaded in mdEditor \(Note: you could have other parent IDs identified in those records, but those records aren't loaded in mdEditor\)

You can drag and drop records to establish the parent-child relationship, eliminating the need to establish the relationship in ScienceBase. This will also allow you to move items around \(e.g., move a product from one project to another\) and have that change be reflected on ScienceBase. Remember, this is only about parent-child relationships on ScienceBase, not about project-product associations.

**General Notes on Parent IDs:**

* If you move a product under a different project, it will update that product’s parent ID.
* Parent IDs established through the relationships in the publishing outline will overwrite existing parent IDs in the metadata.
* Dragging and dropping a record onto the ScienceBase header at the top will set that record’s parent ID to the default parent ID you identified in settings.
* If you have existing parent IDs in your metadata \(and want to keep them as is\), **do not** drag and drop those records onto the ScienceBase header-- this will erase the existing parent ID and insert what you have set as the default parent identifier.
  > ![](/assets/best_practice_small.png)**Best practice: **If you have projects and associated products, make sure you have them in mdEditor at the same time and manage them at the same time.

---

#### Step Two: Moving Records in the Publishing Outline

Before you move records in the publishing outline please select your scenario below and follow the corresponding guidance.

#### Scenario A

_You **do not have** items on ScienceBase yet, and your desired parent-child relationship is to have each product as a direct child of a project item on ScienceBase:_

* Your records will all display under the ScienceBase header in the publishing outline. 
  * These items will be published as a direct child item under the SB item identified in your settings under “Default Parent Identifier.”
* You can **drag and drop **records in the publishing outline to establish parent-child relationships for ScienceBase.
* You can **nest **items in as many levels as you desire \(the most common is a product nested under a project\).
* To move a record back to the root level, drag and drop it on the top line that says “ScienceBase Default”.

#### **Scenario B**

_You** have **existing parent-child relationships on ScienceBase and/or you have intermediate folder\(s\) between project items and products \(i.e., products are not direct child items of Project Items\)._

* If you have parent-child relationships already established on ScienceBase \(and those IDs are reflected in the mdEditor records\), you likely do not want to move the records around in the publishing outline.
* If your products are housed in a “Products” folder on ScienceBase \(or other intermediate folders between the project item and the products\), then your products **will not** be nested under projects in the publishing outline. 
  * The parent ID for those products is the “Products” folder \(which would not have a record in mdEditor\). If this is your situation, do not change  the structure in the publishing outline and publish as is \(i.e., with every item organized at the root level in the outline\).

---

#### Step Three: Submitting for Publishing

1. To select a record to publish, click on it and it will turn green \(click again to un-select it\).

   > ![](/assets/note_small.png)**Note:** You cannot publish a record without a parent ID.
   >
   > * Sending a non-existent parent ID to ScienceBase will return an error.
   > * If records contain parent IDs in the metadata, you can choose to publish products without publishing their parent projects.

2. mdEditor publishes sequentially, starting with the top record \(it will publish the project first, then the products nested below it\).

   * If you are publishing to your _default parent identifier_ or you have changed any project-product relationships in the publishing outline, you will see the updated parent IDs appear in the outline as publishing occurs \(if you’re publishing to the existing locations on ScienceBase, the IDs won’t change\).

   * These new/updated IDs will be injected directly into the mdJSON file in mdEditor. However, these updated IDs will not be included in the mdJSON file that is attached to ScienceBase as part of the publishing process. You would have to publish the record a second time to update the mdJSON file attached on ScienceBase.

3. Upon successfully publishing to ScienceBase, the third column will display a date and time. The record's ScienceBase ID will be displayed in the first column, and the Parent ID will be displayed in the second column.

   If there are any errors during publishing, they will be noted in the third column.

4. Once publishing is done, refresh ScienceBase to ensure everything is showing up how you expected it would show up.

   * SB items should have an mdJSON and xml file attached

   * SB items should be in the location reflected in the mdEditor publishing outline.

5. You can re-publish records as needed \(e.g., after updating or correcting metadata\).



