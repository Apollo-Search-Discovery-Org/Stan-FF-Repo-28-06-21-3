# Accommodation Booking Completed

### 

## Javascript Code
```js
window.appEventData006 = window.appEventData006 || [];
appEventData006.push({
  "event": "Accommodation Booking Completed",
    "booking": {
        "transactionID": "<transactionID>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|transactionID|string|Unique identifier of the transaction. Max Length 20. Used as a key for upload of post transaction data. ||^[a-zA-Z0-9]{6,20}$|6|20||||
