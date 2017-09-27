# openlayers3-vectorlayer-source-update

Example on how to update features for a vector layer by Updating features of a vectory layer every 5 seconds.

## dependencies

* OpenLayers 3
* Apache or XAMPP

## how to use

Put the ol-test folder under `htdocs`. Then go to `http://localhost/ol-test/test.html` in any browser.

## key codes

When a feature update is needed, you just need to change the features property of vector data source:

```javascript
vectorLayer.getSource().clear(); 
vectorLayer.getSource().addFeatures(features); 
```
