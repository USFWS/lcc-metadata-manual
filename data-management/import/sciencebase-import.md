# Importing from ScienceBase

---

The Import function will allow the content files from ScienceBase to be incorporated into the current metadata record.

---

## Method 1:

1. **Copy the ScienceBase ID \(SBID\)** from an existing ScienceBase item 
   The SBID is the string of letters/numbers at the end of the item’s ScienceBase URL 
   * For Example,  "5947e765e4b062508e34424" would be the SBID for an item at the URL [https://www.sciencebase.gov/catalog/item/\*\*5947e765e4b062508e34424a\*\*](https://www.sciencebase.gov/catalog/item/**5947e765e4b062508e34424a**%29%29\)
2. Go to the ScienceBase API address: [https://api.sciencebase.gov/sbmd-service/mdjson/,](https://api.sciencebase.gov/sbmd-service/mdjson/) add the SBID to end of this link, and hit enter. You should see mdJSON text as below.  If not, press enter to search again.

   ## ![](/assets/raw_text_screenshot.png)

3. Right-click in the text area and select “save as” and add “.json” to the end of the file name. This will download the JSON file to your computer.

4. You can either drag the JSON file to the drop box in mdEditor from the download link visible in your browser or from the location on your computer where you saved the file.

5. Review what was imported. Click the “preview JSON” buttons to sort between multiple entries of the same contact, and decide which version to keep.

6. Select the Records and Contacts you want to Import

7. Click on the right-hand button “**Click to Import Data**” to import the selected records

---

## Method 2

Use this method for items where no mdJSON already exists, may or may not have ScienceBase Project facet.

* In Import URL field, paste: [https://api.sciencebase.gov/sbmd-service/mdjson/](https://api.sciencebase.gov/sbmd-service/mdjson/).
  > **NOTE:** You can set default import URL to the "ScienceBase API link" in settings section and it will pre-populate this field. Please refer to the [Settings](/settings.md) section of this manual.
* Copy and paste the **ScienceBase ID \(SBID\) **of the item that you are trying to import at the end of the URL in the import field, and click the **Import** button.
  * The SBID is the string of letters/numbers at the end of the item’s ScienceBase URL. For Example,  "5947e765e4b062508e34424" would be the SBID for an item at the URL [https://www.sciencebase.gov/catalog/item/\*\*5947e765e4b062508e34424a\*\*](https://www.sciencebase.gov/catalog/item/**5947e765e4b062508e34424a**%29%29\)
* Review what was imported. Click the “preview JSON” buttons to sort between multiple entries of the same contact, and decide which version to keep. 
* Select the Records and Contacts you want to Import
* Click on the right-hand button “**Click to Import Data**” to import the selected records



