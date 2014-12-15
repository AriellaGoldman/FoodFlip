FoodFlip

by Ariella Levine (levjam), Louis Petro (petrol), and Elijah Valenciano (elijahv)
========
directory structure:
root has four files in it and four directories. The two files are README.md general_flow.jpg demo-writeup.docx and demo-writeup.pdf. 
The four directories are data, screenshots_and_images, mockups, and src.
data has four files in it: QuestionsCategories.html QuestionTags.html fake_data.xlsx and raw_data.txt
mockups has three files in it: FoodFlipWebsite.jpg, Question_format.jpg, and Questions_search.png
src has one file in it: wordpress_description.txt
screenshots_and_images has ten files in it with various obviously-labelled screenshots.


flow diagram
This is located in the root directory under "general_flow.jpg". The flow diagram describes the general conceptual flow of our project.

QuestionCategories.html
This is the Google Visualization Diagram of the categories of questions

QuestionTags.html
This is the Google Visualization Diagram for the tags associated with the questions

raw data
The raw data is in the "/data" directory. Food Flip doesn't utilize raw_data, so it's a really small file. 

screenshots_and_images/
This directory includes all of the screenshots and images for the project including the header, logo and crowd facing user interface.
It has screenshots from the data page, groups page, homepage and submissions/questions page.

src/
The source folder talks about the details of Wordpress and how we created and structured our website

mockups
All mockups are in the "/mockups" directory. This includes conceptual screenshots and real screenshots of the current website. 
Question_format.jpg and Questions_search.png are screenshots of the current working website. FoodFlipWebsite.jpg is a mockup of what we think we want the homescreen to look like. 

fake_data.csv
This file contains examples of what FoodFlip data will look like. Users submit questions about food recipes and other users submit answers/comments to each of the questions with their suggestions.

The file is ordered as such:

Question	Question_Asker_Username	Question_Time	Question_Categories	Question_Food_Restriction	Question_Votes	Answer_Asker_Selected	Answer1	Answer1_Username	Answer1_Time	Answer1_Upvotes	Answer2	Answer2_Username	Answer2_Time	Answer2_Votes	Answer3	Answer3_Username	Answer3_Time	Answer3_Votes
The Question is required and unique. The Question can include the recipe and all comments or thoughts the Asker might have about the Question. 
The Question_Asker_Username is required (and not unique).
The Question_Time is required (and not unique). 
The Question_Categories is required and can include one of the following options: Baking, Roasting, Cooking, Barbeque, Grilling, Sauteing, Dessert, or Other. 
The Question_Food_Restriction is not required and can include one or many of the following options: Peanut_Allergy, Gluten_Free, Lactose_Intolerant, Nut_Allergy, Kosher, Vegetarian, Vegan, Diabetic. If no option is selected, "None" is defaulted.
The Question_Votes is required and is a number. It can be negative, 0, or positive, and defaults at 0.
The Answer_Asker_Selected is not required. The answer can be "1", "2", "3", and so on, and mnust refer to one of the possible answers given to the question. "None" is defaulted if no Answer is selected. When the Asker posts the question, he cannot submit an Answer Asker Selected because there are no answers to select. He can only select an answer once at least one answer is submitted to his/her question.

There are many possible answers, and each answer has the same data format. 
Answer#	Answer#_Username	Answer#_Time	Answer#_Votes
Answer# is required and can include text, pictures, links, or stories. 
Answer#_Username is required. 
Answer#_Time is required. 
Answer#_Votes starts at 0 and increases or decreases and users vote up or down per answer.

QC and Aggregation

Sample input and output are included in the fake data csv, and the code for it is handled by Wordpress. Note that we are not handing in separate deliverables for sample input/output for QC and sample input/output for aggregation because Wordpress takes care of the things for us. 
This is done using the DW Question and Answer plugin which allows submitting questions and answers.

Thank you!
We tried out best to take care of all of the deliverables that were relevant to our project...but we didn't really know what to do in the general case that "sorry, WordPress deals with all the things.''