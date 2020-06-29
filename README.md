# Resturant_reviews-using-NLP
I am going to apply NLP  and deep learning in the resturant_reviews dataset and gonna find out the positive and negative reviews.
In my code ,first I converted the .tsv file to .csv and then use the pandas library to read the dataset.
After that I split the dataset and then processed all the strings in a for loop.(removings quotes and stopwords).
you can do that by using the tokenizer class of keras in one line.But I thought it would be helpful to go through step by steps.
After all the preprocessing I applied a 1D cnn.
