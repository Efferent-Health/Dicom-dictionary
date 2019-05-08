# Dicom-dictionary
Simple DICOM tag dictionary for JS/TS/ES

The file contains a string-to-string dictionary of DICOM tag numbers and descriptions in a compact fashion, as follows:

````javascript
var DicomDictionary = {
"00000000":"Command Group Length",
"00000001":"Command Length to End",
"00000002":"Affected SOP Class UID",
"00000003":"Requested SOP Class UID",
"00000010":"Command Recognition Code",
// etcetera
````

## Descriptions
The description have been processed from different sources and added spaces, hyphens and slashes in automated and manual ways. There can be some few descriptions that still need to be amended to match the description as in http://dicom.nema.org

## Amendments
Please report any amendment through the [Issues](https://github.com/Efferent-Health/Dicom-dictionary/issues) page, but preferably via the [Pull Requests](https://github.com/Efferent-Health/Dicom-dictionary/pulls) page
