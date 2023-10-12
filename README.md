# SwaggerApiTesting
## :page_facing_up: API Test Report
## :memo: How to run this project
### 🖥 Run by Postman
* Clone this repository.
* Import collection and environment file/link.
* Run the collection on Postman.
### 🖥 Run by Newman
* Clone this repository.
* Open cmd to the file location.
* Run Command:
```console
newman run CRUD.postman_collection.json -e CRUD.postman_environment.json
```
* Run Command for Report:

For html:
```console
newman run CRUD.postman_collection.json -e CRUD.postman_environment.json -r cli,html
```
For htmlextra:
```console
newman run CRUD.postman_collection.json -e CRUD.postman_environment.json  -r cli,htmlextra
```
### :technologist: Technology used
<img src="https://voyager.postman.com/logo/postman-logo-icon-orange.svg"  width="15" height="15"> Postman & Newman

### Prerequisite
- Jdk
- Node Js
- Newman
- Html Report Library

### Newman and Report Installation Process
- Newman Install Command:
``` console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
``` console
npm install -g newman-reporter-htmlextra
```
### API Documentations
https://petstore.swagger.io/#/user/logoutUser
#### Postman Documentations
[Postman](https://web.postman.co/documentation/24594715-60df2812-f92f-408a-9e41-4f2ec7ef516e/publish?workspaceId=7b4e508f-1253-4e33-8843-0cc4fd3138d4)
# Newman Report
![image](https://github.com/Sayid1218/SwaggerApiTesting/assets/97175166/4f4abb3b-5245-48fe-9ec4-6ee1025f8262)
![image](https://github.com/Sayid1218/SwaggerApiTesting/assets/97175166/93e2f8e8-5de8-4c17-9225-2aa80f063d11)


