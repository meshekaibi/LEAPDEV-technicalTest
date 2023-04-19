# LEAPDEV-technicalTest
This is answert to Task 2 of the technical test for LEAPDEV QE Engineer role

# Introduction
This repository contains a Postman collection file that can be imported to Postman. The collection file contains a REST API automated testing in testing all the CRUD endpoints listed on https://crudcrud.com/. 

NOTE: 
Before running the automation, an api_key needs to be taken from https://crudcrud.com/ and copy it as part of the collection variable. 

There will be instructions on how to use the Postman collection file. 

# How to import the collection file in Postman
1. You can download the repository as a zip file by clicking "<> Code" dropdown menue and selecting Download ZIP
![image](https://user-images.githubusercontent.com/68898560/232931606-f14b4609-a6d0-4efd-be98-d975f3482f16.png)
2. Download and extract the LEAPDEV-technicalTest-main.zip file on your machine 
3. Open Postman application
4. In Scratchpad, click Import
![image](https://user-images.githubusercontent.com/68898560/232934717-d840552a-be18-4b9a-af85-d3fbd9131535.png)
5. click Upload Files
![image](https://user-images.githubusercontent.com/68898560/232934779-49b05170-778c-458e-9d6e-5cb56ea2ce01.png)
6. Navigate to the LEAP-Techical_Test.postman_collection.json file that was downloaded and extracted earlier and select the file. 
7. Click Import button
![image](https://user-images.githubusercontent.com/68898560/232934964-b6f89e45-8a7f-4f15-83c4-864ffd81f33a.png)

# How to get api_key from https://crudcrud.com/ and import in Postman collection as collection variable
1. Open browser and navigate to https://crudcrud.com/
2. Copy the api_key that is shown in the page https://crudcrud.com/api/{api_key}. In this example, the api_key is "8c71ed0487844d2b85f06f6dbe941d1b"
![image](https://user-images.githubusercontent.com/68898560/232935801-4e5399cb-efc2-465a-9cf5-be90e5c2f7e9.png)
3. Go back to Postman and click LEAP-Technical_Test collection
![image](https://user-images.githubusercontent.com/68898560/232935903-56177739-c0b6-4320-95a4-7ddec0de8409.png)
4. Click Variables tab and past the copied api_key from crudcrud.com to Initial Value and Current Value of variable api_key
![image](https://user-images.githubusercontent.com/68898560/232936180-4d476459-3984-4ba9-9bbb-b09e8cb9f775.png)
5. Click Save collection
<img width="1919" alt="image" src="https://user-images.githubusercontent.com/68898560/232941542-f9849f15-e5f1-4c14-9064-a5b58a7b32fd.png">

NOTE:
All Employee properties are set as collection variable. The values can be changed easily from the variable-key value pair and are not hard coded in the request body.

# How to run the collection runner
1. In Postman and click LEAP-Technical_Test collection
<img width="482" alt="image" src="https://user-images.githubusercontent.com/68898560/232941833-a0ad7e05-4fa9-4c70-beb6-6e573eb9ee9d.png">

2. Click "Run" icon
<img width="1930" alt="image" src="https://user-images.githubusercontent.com/68898560/232943322-71224863-5985-466a-a587-1e129df8bcc8.png">

3. Click "Run LEAP-Technical_Test" button
![image](https://user-images.githubusercontent.com/68898560/232943347-4bd0ff19-c729-471b-93ef-ab5e9dad83ee.png)

4. View the result 
![image](https://user-images.githubusercontent.com/68898560/232943402-55df611a-0af8-401e-a6cf-4c6c0d8100f1.png)

NOTE:
Post request with name of "POST FirstName value as Integer" has failed in testing because https://crudcrud.com/ does not support schema validation in post requests. 

