# Sprint 4

## Frontend:
- needs component that handles Success and Error messages on all forms, so that they are not persistent (update state).
- needs tests.
- general err / bug fix 


___

### 2453
upload products: as a representative I want to see a list of my company's products to have quicker access to them
### 2452
add product: as a representative i want to upload materials for my products so that my customers can have access to it

**Representative** should be able to:  

n    |  tasks                      |  frontend            |  backend      
 --- | --------------------------- | -------------------- |  ---------       
1    | list all Company’s Products |		  UI page: list		|	 API get all company’s products   
2    | create Product			         |   UI page: register product	|	API post product  
3    | view Product from List	    |	UI page: view product	|	API get product  
4    | upload PDF from Product   	|	control to upload files	|	API file upload  

___


### 2599
ratings: as a consumer i want to rate an individual piece of material in terms of whether i find it useful or not, to help other users and to express my opinion

**Consumer** should be able to:  

n    |  tasks                      |  frontend            |  backend      
 --- | --------------------------- | -------------------- |  ---------       
1    | see individual rating for each material on product page  |   UI stars on Product Page  |   ?
2    | view/expand material info on product page  |   UI page: material component	|	?     
3    | rate material (once?)    |	UI dynamic rating/stars component	|	API post rating  
4    | see material’s average rating   	|	-	|	API get average rating + N of votes  



### 2593
annotations: as a consumer i want to associate some notes of my own to a piece of material so that i don't have to remember insights/solutions that resulted from consuming some material

**Consumer** should be able to:  

n    |  tasks                      |  frontend            |  backend      
 --- | --------------------------- | -------------------- |  ---------  
1  |   view/expand personal notes for each material   |  -            |  -              
3  |   edit notes 		|     UI comment component		|     API get/post consum/prod/material/comment

![material](https://raw.githubusercontent.com/2dv612-team-1/sprint-04/master/material-page.jpeg "Material")

___

### 2602
As a system admin I want to be able to create subcategories so that searching can be fine tuned.

**Admin** should be able to   

n    |  tasks                      |  frontend            |  backend      
 --- | --------------------------- | -------------------- |  ---------  
1    |  list all Product Categories + Subs	|    UI page: list			|    API get all categories+subs  
2    |   create Subs for Category		|   UI page: register subcategory	   |    API post subcategory  


![categories](https://raw.githubusercontent.com/2dv612-team-1/sprint-04/master/subcategories.jpg "Categories")

