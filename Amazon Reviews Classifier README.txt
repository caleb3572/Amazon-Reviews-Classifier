Make sure you have my Colab notebook containing the program as well as my zipped folder containing the train/test data.
Although the instructions are also in the Colab notebook, they are also in this file.

Once you have opened my Colab notebook, do the following to experience the program:
1. Start the Colab notebook and open the Files tab.
2. Make sure you are in the "content" folder (the folder with the "sample_data" folder)
3. In the "content" folder, create two folders named train_data and test_data
4. You should have a zipped file with data that has either the word "train" or "test" in its name. Put the "train" data in the train_data folder and the "test" data in the test_data folder.
5. Run the code cell that says "Train Phase." It will create word sentiment weights that can then be used for determining sentiment of topics.
6. Run the code cell with the "is_noun_or_unknown" function, which is needed for the test phase.
7. Run the code cell that says "Test Phase." This is where the program determines the average sentiment of topics/subtopics by category with 10,000 reviews for each category.
8. After running the Test Phase code cell, you can run other code cells to create various charts. You can create a top 10 most positive/negative topics by category, find the score of a specific word in a category, or create bar graphs representing the score of a specific word for each category.
9. You are also able to find the sentiment of words using only one review by running the last code cell and specifying the review's title and text (after running the Train Phase and is_noun_or_unknown code cells).

Note: Some lines of code that are commented out are there for the purpose of debugging.

Category legend (train_data): acs=Arts Crafts and Sewing, books=Books, cpa=Cell Phones and Accessories, csj=Clothing Shoes and Jewelry, electr=Electronics, hk=Home and Kitchen, matv=Movies and TV, spo=Sports and Outdoors, thi=Tools and Home Improvement, vg=Video Games

Category legend (test_data): books=Books, cpa=Cell Phones and Accessories, ggf=Grocery and Gourmet Food, hk=Home and Kitchen, matv=Movies and TV, plg=Patio Lawn and Garden

Refer to my google slides presentation for more information on this program.
