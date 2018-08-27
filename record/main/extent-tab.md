# Project Entry Guidance: Extent Tab

---

**Extent** refers to geographic boundaries for your project. Spatial extents lets users see at a glance the geographic footprint of your project and allows searching within specific geographic areas.

---

## Creating Extents

There are multiple ways to create a spatial extent for your project.



Clicking the **Edit Extent Features **button allows for the addition of **Feature Properties **such as: **ID,** **Name,** or **Description**. You can draw polygon or a bounding box in the initial window.

You can export spatial extents and re-use for other records using the **import feature **button or by dragging and dropping onto the map. 

Extents should be accurate enough for searching purposes, but remember that they are metadata, not data.

### Option 1: Import Spatial Features

Spatial features such as geoJSON, shapefiles, and kml can be imported. However, file attributes \(such as name and description\), will not be imported. Extents are limited to 5000 vertices. Recommend you create only simple polygons or bounding boxes. If you want greater detail, attach high-definition shapefiles instead of trying to draw them.

File attributes \(such as name and description\) will not be imported and must be added manually.

> Important: coordinates used must be geographic coordinates, not projected coordinates.

### Option 2: Draw Spatial Features

> Tip: It is easier to click "finish" when drawing a polygon instead of trying to close the polygon by clicking on the first point.

### Option 3: Draw Bounding Box

> Danger: Bounding boxes will not work across the dateline but you can have more than one extent per project. If your project area crosses the dateline, split the area into multiple extents and create separate bounding boxes.

## Saving and Exporting Extents

> Tip: You can export, save, and import an extent to use for other projects or products.



![](/assets/extent_screenshot.png)

![](/assets/edit_extent_page.png)

> For more information, consult the [**Extent**](https://adiwg.gitbooks.io/mdeditor/content/record/edit/record-extent.html) section of the mdEditor manual.


