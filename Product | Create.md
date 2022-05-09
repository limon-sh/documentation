|Action | Description | 
| ------ | ------ |
| Fields |1. Name (mandatory, unique, 64 char), otherwise error and not allow to create a product 'Please provide name' OR 'The name should be less than 64 characters' OR 'The product name should be unique'|
||2. Logo (optional, 5MB, JPEG, PNG, otherwise error and not allow to create a product 'The file format should be .jpeg or .png' OR 'The file name should be less than 5MB'. The system should not support manual crop of the photos.|
|Logic of creation|1. The user with roles 'Admin','Owner' should be able to create products
||2. The user should be able to create product within the organization only|
||3. The user should be able to create products without limits in amount|
||4. As soon as the system confirms that the product can be created in the system the system should: add product in the system AND provide access to the product to all users with the role 'Admin' of the selected organization and to the user with the role 'Owner'|
