# t2 

Pang Jing Hui | P1845259

## Web API Document
| No. | HTTP Method  | Route | Description |
| ------------- | ------------- | ------------- | ------------- |
| 1. | GET  | api/v3/products  | Retrieve all the data.  |
| 2. | GET  | api/v3/products/{id:int:min(1)}  | Retrieve data based on id. Route constraints let you restrict how the parameters in the route template are matched. The general syntax is "{parameter:constraint}". Constraints on URL parameters. We can even restrict the template placeholder to the type of parameter it can have. For example, we can restrict that the request will be only served if the id is greater than 1. Otherwise the request will not work.   |
| 3. | GET  | api/v3/products?category={category}  | Retrieve the data by cateogry   |
| 4. | POST  | api/v3/products  | Create/add a new data. NOTES: Response code: By default, the Web API framework sets the response status code to 200 (OK). But according to the HTTP/1.1 protocol, when a POST request results in the creation of a resource, the server should reply with status 201 (Created). Location: When the server creates a resource, it should include the URI of the new resource in the Location header of the response.  |
| 5. | PUT  | api/v3/products/{id:int}  | Update/edit a data. The general syntax is "id:int" where the id must be integer.  |
| 6. | DELETE  | api/v3/products/{id:int}  | Delete/remove a data. Applied same restriction.   |


## Postman testing screenshots
### 1. GET (ALL)
![](images/get.png)




