FoodFlip

by Ariella Levine (levjam), Louis Petro (petrol), and Elijah Valenciano (elijahv)
========

fake_data.csv
This file contains examples of what FoodFlip data will look like. Users submit questions about food recipes and other users submit answers/comments to each of the questions with their suggestions.

The file is ordered as such:

Question	Question_Asker_Username	Question_Time	Question_Categories	Question_Food_Restriction	Answer_Asker_Selected	Answer1	Answer1_Username	Answer1_Time	Answer1_Upvotes	Answer1_Downvotes	Answer2	Answer2_Username	Answer2_Time	Answer2_Upvotes	Answer2_Downvotes	Answer3	Answer3_Username	Answer3_Time	Answer3_Upvotes	Answer3_Downvotes
The Question is required and unique. The Queston can include the recipe and all comments or thoughts the Asker might have about the Question. 
The Question_Asker_Username is required (and not unique).
The Question_Time is required (and not unique). 
The Question_Categories is required and can include one of the following options: Baking, Roasting, Cooking, Barbeque, Sauteing, or Other. 
The Question_Food_Restriction is not required and can include one or many of the following options: Peanut_Allergy, Gluten_Free, Lactose_Intolerant, Nut_Allergy, Kosher, Vegetarian, Vegan, Diabetic. If no option is selected, "None" is defaulted.
The Answer_Asker_Selected is not required. The answer can be "1", "2", "3", and so on, and mnust refer to one of the possible answers given to the question. "None" is defaulted if no Answer is selected. When the Asker posts the question, he cannot submit an Answer Asker Selected because there are no answers to select. He can only select an answer once at least one answer is submitted to his/her question.

There are many possible answers, and each answer has the same data format. 
Answer#	Answer#_Username	Answer#_Time	Answer#_Upvotes	Answer#_Downvotes
Answer# is required and can include text, pictures, links, or stories. 
Answer#_Username is required. 
Answer#_Time is required. 
Answer#_Upvotes starts at 0 and increases as other users upvote the answer. The number cannot be less than 0.
Answer#_Downvotes starts at 0 and increases as other users downvote the answer. The number cannot be less than 0.