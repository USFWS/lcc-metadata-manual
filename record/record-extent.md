# Record Extent

---

> ![](/assets/project_required_small.png)**Record Extent is required for Projects Only**

**Record Extent** refers to geographic bounds for the project. It is recommended that you use an extent since they can be used to populate Congressional districts once that capability is available.

![](/assets/extent_screenshot.png)Clicking the **Edit Extent Features** button allows for the addition of **Feature Properties **such as: **ID**; **Name**; or **Description**. You can draw a polygon or a bounding box in the initial window.

It is possible to export bound features and re-use for other records using the **import feature **button or by dragging and dropping onto the map \(i.e. set up standard geographies\). Features such as geoJSON, shapefiles, and kml can be imported. However, file attributes \(such as name and description\), will not be imported.

> ![](https://adiwg.gitbooks.io/mdeditor/content/assets/note_small.png)
>
> **Note: **Bounding boxes will not work across dateline. However, you can have more than one extent, so if your area crosses a dateline, split the area and create separate extents.
>
> **Note**: The extent must use geographic coordinates, not projected coordinates
>
> ![](/assets/best_practice_small.png)
>
> **Best Practice**: If you are unsure of your projects extent, enter the coordinates of your LCC boundary in the bounding box.
>
> **Best Practice: **Shapefiles are limited to 5000 vertices. It is recommend that you create only simple polygons or bounding boxes. If you want greater detail, attach high-definition shapefiles instead of trying to draw them.
>
> **Best Practice: **Extents should be accurate enough for searching purposes, but remember that they are metadata, not data.

![](/assets/edit_extent_page.png)

