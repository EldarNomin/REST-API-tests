# REST-API-tests

[A1QA] Study project 

Site: https://jsonplaceholder.typicode.com
|Step|Expecting result|
|:----|:----------------|
Test case 1
|Send GET Reques t to get all posts (/ posts).| Status code is 200. The list in response body is json. Posts are sorted ascending (by id).|
Test case 2
|Send GET request to get post with id=99 (/ posts /99).| Status code is 200. Post information is correct: us erId is 10, id is 99, title and body aren't empty.|
Test case 3
|Send G ET request to get post with id=150 (/posts /150).| Status code is 404. Response body is empty.|
Test case 4
|Send P OST request to create post with userId= 1 and random body and random title (/p osts).| Status code is 201. Post information is correct: title, body, userId match data from request, id is present in response.|
Test case 5
|Send G ET request to get users (/ users).| Status code is 200. The list in response body is json. User (id=5) data equals to:name:ChelseyDietrichusername:Kamrenemail:Lucio_Hettinger@annie.caaddress:street:SkilesWalks suite:Suite351city:Roscoeviewzipcode:33263geo:lat:-31.8129lng":"62.5342"phone:(254)954-1289, website:demarco.infocompany:name:KeeblerLLC,catchPhrase:Usercentricfault-tolerantsolutionbs:revolutionizeendto-endsystems |
