# Admin: Create a publication

The user with the role admin should be able to create a publication. To do this the user should be able to provide the following data:
1. Publication name (mandatory, 256 char)
2. Publication picture (mandatory, pang, jpg, jpeg, up to 5 MB)
3. Publication text (mandatory, 15000 char). Within the provided text the system should determine: links, headers, font size, font colour, space between the text, markers 
4. Author (by default the current user should be pre-selected. The user should be able to select an author that is in the system)
5. Tags (there is no limitation in amount, the user should be able to select tag(s) from the already created ones within the system)
6. Provide visibility: published, unpublished 
7. Provide first position: yes, no

As soon as the user confirms the publication creation the system should:
1. save it within the system 
2. display in the list of publications within the admin panel
3.  publish it to the Blog page of web-site (if "published" option is selected)
4. make the publication first, if there is statement is true (the following action should be applied for the publication if the statement is true: as soon as the new publication is saved, the system should exclude first publication is "true" for the previous published publication (if there was) and assign this mark to the current publication) 

The system should store 3 types of dates for the publication:
1. date of creation
2. date of the latest edit 
3. date of the lates visibility = published  

# Admin: Delete a publication
The user with admin role should be able to delete a publication. A soon as the action is confirmed the system should delete publication from the system without ability to restore it. 

# Admin: View + Edit a publication
The user with admin role should be able to edit publication (see fields from Create publication, the same rules should be applied). As soon as the user confirms editing the system should apply changes 

# Admin: View details + Edit a publication
The user with admin role should be able to edit publication (see fields from Create publication, the same rules should be applied). As soon as the user confirms editing the system should apply changes 

# Admin: View  publications list
The user with admin role should be able to view the list of publication that exists in the system with the following data:
1. publication name
2. publication author
3. publication tags
4. visibility 
5. is first
