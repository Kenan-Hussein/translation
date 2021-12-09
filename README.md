# Translation Schema V 1.0.0

- 'data' object is main entry with main language
- Using 'translate' object in request will be the mark to tell that we have another language(s) for this item.
- It will help detrmine wheather should save or update this item in the translate table for this item.
- 'itemId' will be use for update or delete

```json
{
    "data": {
        "itemId": "",
        "lang": "",
        "storeCategoryName": "",
        "description": ""
    },
    "translate": [
        {
            "itemId": "",
            "lang": "",
            "storeCategoryName": "",
            "description": ""
        },
        {
            "itemId": "",
            "lang": "",
            "storeCategoryName": "",
            "description": ""
        }
    ]
}
```