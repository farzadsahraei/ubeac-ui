# UBreadCrumb

## Properties

### dir

* type: string
* default: right
* available values: left, right

### visible

* type: boolean
* default: true

### class

* type: String

### items

* type: JSON, Array
* ExampleJSON : {"Text":"itemtitle","Link":"1","ActiveLink":"true",,"tooltip":"..."} 
* ExampleArray : [["itemtitle","1","true","..."],["itemtitle2","2","false","..."]]

## Methods

onLoad

onChange

## Examples

```html
<u-breadcrumb visible="true" label="" items="" autofocus="false" class="" @change="" />
```
