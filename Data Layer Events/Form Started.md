# Form Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "Form Started",
    "ecommerce": {
        "location_name": "<location_name>"
    },
    "event_data": {
        "form_field_id": "<form_field_id>",
        "form_id": "<form_id>",
        "form_type": "<form_type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|form_field_id|string|Captures the upper end of a point range for an offering||||||||
|form_id|string|Captures the point-to-point distance from map POI \(point-of-interest\).|F-0113, 2543, CU001, PI-0988|||||||
|form_type|string|Captures the currency code of a specific item in a listing.|Address, Contact, Comment, Review, Payment|||||||
|location_name|string|Captures the number of events displayed in an event listing.|Deerefiled Outlet, Old Orchard, Manhatten Midtown|||||||




