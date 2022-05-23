|Action | Description | 
| ------ | ------ |
| Fields |1. Name (mandatory, unique, 64 char), otherwise error and not allow to create a product 'Please provide name' OR 'The name should be less than 64 characters' OR 'The product name should be unique'|
||2. Logo (optional, 5MB, JPEG, PNG, otherwise error and not allow to create a product 'The file format should be .jpeg or .png' OR 'The file name should be less than 5MB'. The system should not support manual crop of the photos.|
||3. Members: by defaul the user who've created the project should be uneditable until the new memeber with the same or highest permission will be added to the product.|
||The user should be able to search for members by first name, las name and email. The syste, should search by the provided order of letters from the beginning. The system should show suitable results and allow to scroll them. The system should sort results by the alphabetical order by the word where the search has been applied (if first name, last name and email has the same order of letters the system shoukd show first name as the key one. The system should highlight the suitable part of the word. The system shoukd update results as soon as the new symbol as added or removed. The system should start search from the first symbol.|
||The system should allow to add unlimited amout of unique memebrs. If the member is added the system shoukd not show them in search results.|
||The user should be able to assign the role that is less or equal in terms of permissions. By default all memebers should be added with the **TBD**|
|Logic of creation|1. The user with roles 'Admin','Owner' should be able to create products
||2. The user should be able to create product within the organization only|
||3. The user should be able to create products without limits in amount|
||4. As soon as the system confirms that the product can be created in the system the system should: add product in the system AND provide access to the product to all users with the role 'Admin' of the selected organization and to the user with the role 'Owner'|
