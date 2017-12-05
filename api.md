# API endpoints

## 2602
As a system admin I want to be able to create subcategories so that searching can be fine tuned.

https://nanotu.be/categories
GET  
gets all categories
```javascript
[
	{category: 'car', sub: [{category: 'gocart'}, {category: 'golfbil'}, {category: 'monstertruck'}]},
	{category: 'animal', sub: [{category: 'giraffe'}, {category: 'elephant'}]}
]
```

https://nanotu.be/categories 
POST   
Creates a new **main** category. Requires the following data:

```javascript
{ 
  "jwt": "an.admin.jwt",
  "category": "new-category-name"
}
```

Creates a new **sub** category. Requires the following data:

```javascript
{ 
  "jwt": "an.admin.jwt",
  "parent": "existing-category-name",
  "category": "new-sub-category"
}
```

___
