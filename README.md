# Standards
ITEM Definition
```js
{
"base_req": {
"from": "idep1mc3t0cye333achqg6enw2nkfmftxja4x3mt0zh",
"chain_id": "Test-Denali"
},
"id": 'String',
"name": 'String',
"transferable": 'bool',
"owner": "idep1mc3t0cye333achqg6enw2nkfmftxja4x3mt0zh",
"recipient": "idep1mc3t0cye333achqg6enw2nkfmftxja4x3mt0zh",
"denom_id": "kingsword99",
"uri": "URI",
"metadata": "URI",
}
```
ITEM Metadata
```js
{
    "description": 'String',
    "name": 'string',
    "attributes": ['String1','String2',...],
    "images": [ // multiple images in different sizes, related to the Item, image 0, should be the main image
            [
                {
                    "width": Number,
                    "height": Number,
                    "url": 'string'
                },
                ...
            ],
            [...]
        ],
}
```
