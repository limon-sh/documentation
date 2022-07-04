# Client: Blog list
The user of the blog page should be able to view the following info:
| Data |Description  |
|--|--|
| First publication | The publication that has "is first" mark |
|Search|Search should work by publication name and tags. As soon as the user start typing the system should start |
|Tags list|The system should display the list of tags that exists in the system|
|Publication list|The system should sort publication by publication date (newest at the top). The system should display 9 publications at the page. Pagination should be supported. |
|Single publication preview|The system should display the following information for each publication: picture, name, date of publication, reading duration (see calculation below), text (about 100 chart),publication tags)|
|Reading duration|The system should calculate the reading duration time by the formula: amount of words/285 (words per minute). The system should use mathematic rounding. The final value should be integer|

The user should be able to access publication details by clicking the publication. 


# Client: Blog - Publication details
The system should display the following data for the publication details:
1. Date of publication 
2. Reading duration
3. Publication title
4. Publication picture
5. Publication text
The system should recognize font size, font, colour, hyperlinks, emodji 
6. Author photo
7. Author description 
8. Author position 
9. Publication categories
10. Related publication (4 items)
 The related publication should be determined by sorting the whole list of publications within the system (the selected publication should be excluded from the list) and sorted by the tags (the publication with the majority of matches should be at the top).
