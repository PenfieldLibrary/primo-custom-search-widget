# primo-custom-search-widget
## Description

This form search widget to add to a library website

## Use

1. Copy both the <b>script</b> and the <b>form</b> and embed it in your html page

2. Change the following code with you Library Primo URL and code:
    ```html
    <form id="simplelimit" name="searchFormlimit" method="get" target="_blank" action="<Your-Primo-Library-URL>/discovery/search"

    <input type="hidden" name="vid" value="<Your-Primo-Library-Code>">
    ```
3. Change the  value {books} with the resource type you want:
    ```html
    <input type="hidden" name="mfacet" value="rtype,include,{books},1">
    ```

## Adding additional facets. (optional)
1. duplicate this line
```html
 <input type="hidden" name="mfacet" value="rtype,include,{books},1">
```
2. Change the value {books} with the resource type you want.

Example:
```html
<input type="hidden" name="mfacet" value="rtype,include,books,1">
<input type="hidden" name="mfacet" value="rtype,include,journals,1">
```
