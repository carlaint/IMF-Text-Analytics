Restrictions with our network computers challenges me to be more creative with my coding.

Our office laptops do not allow us to call Python packages that are not vetted by our IT department, which means I am confined to using the main packages like Pandas, scikitlearn, and matplotlib.

And while there is a growing need for text analysis, particularly text search, in my day-to-day work, I thought it may be more efficient to code a workaround, i.e. for a keyword search that uses strictly Pandas.

What the code does is the following.
* loops over each text file in a given folder (there is an intermediate step of converting pdfs to txt)
* converts each word to lowercase (this helps me skirt the case-sensitivity issues of text search)
* searches for a given set of keywords
* returns the total word occurences in a given folder
* returns the line in the text with the given word, as well as the preceding, and succeeding line. 
* outsheets the results in excel.

The code is viewable <a href="https://github.com/carlaint/IMF-Text-Mining-Projects/blob/master/Text%20search%20-%20loop%20over%20a%20list%20of%20words.ipynb">here</a>.
