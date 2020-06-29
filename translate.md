# Translate

---

The **Translate **function allows for translation and export of a record into another file format. Translation works to the following formats: ISO 19115-2, ISO 19110, HTML, or sbJSON \(ScienceBase JSON\). The mdTranslator tool is integrated with mdEditor so you can create metadata once, and then convert and publish the metadata in your desired format, such as mdJSON for the LCC Science Catalog, sbJSON for ScienceBase, XML for data.gov, and FGDC for geospatial data.

---

 **Translate** is only visible when you’re viewing a metadata record.

### ![](/assets/translate_screenshot.png)

**How mdJSON Works With the mdTranslator**

mdTranslator is an open-source Ruby software application for translating between metadata standards. Metadata is input in one of the supported ‘reader’ formats and output in one of the supported ‘writer’ formats. Available as Ruby gem or Command-Line-Interface.

mdTranslator inputs mdJSON \(or any other reader formats: sbJSON; FGDC; or CSDGM\). The translator reformats the file into any of the selected writer formats: ISO 19115-2; ISO 19110; HTML; mdJSON; FGDC; CSDGM; ISO 19115-1; or sbJSON.  It then outputs the selected file format.![](/assets/translator_diagram.png)

