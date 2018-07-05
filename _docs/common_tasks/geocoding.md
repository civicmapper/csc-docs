---
title: Geocoding an Excel Table
permalink: /docs/geocoding/
---

# Setup

To geocode locations in an excel table, it is necessary to install the [ArcGIS Excel Add In](https://doc.arcgis.com/en/maps-for-office/). Note that this product is not compatible with Mac operating systems. The user must also have a **feature class** available in their ArcGIS Online account to which the data can be linked.

_BEFORE YOU START_

Make sure that the two fields (columns) of data you will be linking are in the *same format*. Note the names of these fields.
    -   To join the two fields, the values must match exactly.
    -   The join will be case sensitive
    -   For example 'G123' will not match with 'G_123'

**Viewing an Attribute Table in ArcGIS Online**

*   Sign in to ArcGIS Online and navigate to the **Content** page.
*   Navigate to the relevant feature class.
*   Select the **Data** tab.
*   Attribute table will display.
	-   If there are multiple layers in the feature class, select the relevant layer from the dropdown menu.

In this example a table containing parcel data will be linked to a parcel boundary feature class using the **PIN number** attribute.

![Demo of Excel to Parce Layer workflow]({{site.img_folder}}ComparingPINFields.gif)

***

# Creating the Map

First, select the **ArcGIS Maps** tab in Microsoft Excel and sign in to your ArcGIS Online account.

![Demo of Excel to Parce Layer workflow]({{site.img_folder}}ExceltoParcelLayerDemoClip1.gif)

## Selecting the Data to be Geocoded

-  Click Add Map and select the **Cell range** option.
    * Use your cursor to select the records you would like to geocode, then click OK.

    ![Demo of Excel to Parce Layer workflow]({{site.img_folder}}SelectingCellRange.gif)

## Creating the Geocoder 

-  Click on the **Location Type** drop down menu and select **More**.
    * Then click on the **My Locations** tab.

![Demo of Excel to Parce Layer workflow]({{site.img_folder}}SelectingLocationType.gif)

<br>
-  Click on **Add Location Type** and then find the feature class containing the spatial data you want to use to geocode your table. This can be done by navigating to the ArcGIS Online folder containing the correct feature class or by using the search bar.

![Demo of Excel to Parce Layer workflow]({{site.img_folder}}SearchLocationTypeFeatureClass.gif)

<br>
-  Once the appropriate layer is selected, use the drop down menu to choose which layer of the feature class you are using as the location layer for geocoding. If the feature class contains only one layer, this step may not be necessary.

![Demo of Excel to Parce Layer workflow]({{site.img_folder}}ChooseGeocoderLayer.gif)

<br>
-  Choose the field you are using to link to your Excel table data. In this case, the **PIN** field in the feature class will link with the **Parcel Number Alternate** field in the table.

![Demo of Excel to Parce Layer workflow]({{site.img_folder}}ChooseGeocoderLinkAttribute.gif)

## Geocoding the Data

-  Click the drop down menu to choose to match the **Parcel Number Alternate** column to the PIN feature class field. 
    *   Note that in Step 3, **Style by Column** there are many options for data display. In this example, **none** is selected, so that the polygons will display as a simple fill. 
    *   In the **Choose a way to visualize your data** area, there are display options to browse if a field is selected in the **Style by Column** drop down. When **none** is selected, this simplifies to one option.

![Demo of Excel to Parce Layer workflow]({{site.img_folder}}LinkingColumnsSimpleSymbolize.gif)

<br>
-  Select **Add Data** and wait for the map to draw. Once the data is linked to the polygon layer, some display options like drawing scale and transparency are available to fine tune. Click OK once the layer is displayed in the way wanted.

![Demo of Excel to Parce Layer workflow]({{site.img_folder}}LayerAddedToMap.gif)

***

# Sharing your Data

-  To share your new layer to your ArcGIS Online account, click on the ‘Share Layer’ tool and fill in the required fields. Note that the groups you choose to share your layer with will be able to access the uploaded feature class on ArcGIS Online.

![Demo of Excel to Parce Layer workflow]({{site.img_folder}}SharingNewMap.gif)

<br>
-  To check that the layer was properly shared, log on to the ArcGIS Online website and navigate to ‘Content’. View the layer by clicking on it and then selecting ‘Open in Map Viewer’

![Demo of Excel to Parce Layer workflow]({{site.img_folder}}CheckSharingOnline.gif)