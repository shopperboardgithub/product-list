# ShopperBoard Product 

```JSON
[
  {
    "id": "",
    "title": "",
    "url": "https://producturl.com/product/test123",
    "price": 39,
    "usualPrice": 45,
    "currency": "SGD",
    "isBackorder": false,
    "isRestock": false,
    "isSoldOut": false,
    "published_at": "2021-10-28T11:31:26-07:00",
    "created_at": "2021-10-28T11:31:27-07:00",
    "updated_at": "2021-10-28T11:33:09-07:00",
    "images": [
      "https://test.com/images/test1.jpg",
      "https://test.com/images/test2.jpg",
      "https://test.com/images/test3.jpg"
    ],
    "description": [
      {
        "title": "Description",
        "body": "<div><h4>FULL DESCRIPTION</h4>Description<ul><li>Rounded neckline collar with front slit</li><li>Dropped shoulder</li><li>Slight puff sleeves</li><li>Fabric: Cotton</li></ul><h5>PRODUCT CODE: ABB0009470Y</h5><table><tbody><tr><td>Inches</td><td>S</td><td>M</td><td>L</td><td>XL</td></tr></tbody><tbody><tr><td>Shoulder</td><td>19.5</td><td>20</td><td>20.5</td><td>21</td></tr><tr><td>Bust</td><td>38</td><td>40</td><td>42</td><td>45</td></tr><tr><td>Hem</td><td>40</td><td>42</td><td>44</td><td>47</td></tr><tr><td>Length</td><td>23</td><td>23.5</td><td>24</td><td>25</td></tr></tbody></table><p>Model wears: M, UK 10, EUR 38<br>Model&#x2019;s height: 174 cm/5&#x2019;9&#x201D;</p><p><strong>LOOK AFTER ME</strong><br>Machine&#xA0;Wash According To Instructions On Care Label.<br>Hand washes preferred.</p></div>"
      }
    ],
    "variants": [
      {
        "id": "",
        "sku": "",
        "price": 40,
        "usualPrice": 50,
        "grams": 80,
        "images": [],
        "quantity": 8,
        "option": {
          "Size": "Small"
        }
      }
    ],
    "options": [
      {
        "name": "Size",
        "values": [
          "Small",
          "Medium",
          "Large"
        ]
      }
    ]
  }
]
```


## Properties

### Product
| Name | Description |
|------------|----------|
| id | an unique identifier for product, number or string. |
| title | product name |
| url | product url |
| price | product selling price. |
| usualPrice | product usual price. |
| published_at | The date and time when the product was published. optional. |
| images | A list of product image |
| description | A list of description for the product, supports HTML formatting. Supports multiple type, e.g. shipping description, size description. |
| variants | The Product resource will have a variant for every possible combination of its options. Each product have a variant at least. |
| options | The custom product properties. For example, Size, Color, and Material. Product variants are made of up combinations of option values.|
 
### Variant
| Name | Description |
|------------|----------|
| id | an unique identifier for product, number or string. |
| sku | product sku. |
| price | product selling price. |
| usualPrice | product usual price. |
| grams | The weight of the product variant in grams. |  
| images | A list of product image, optional. |
| quantity | Product inventory |
| option | The custom product properties. |