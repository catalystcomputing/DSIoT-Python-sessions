# Plan

- Convert to dictionary and vectorise
- Vectorise description text by word
	- Try stop words
- Combine Whole description string, vectorisd and vectorise description text by word
- Add spell checking
	- Remove duplicate rows after spell checking
- Where multi entries per barcode exists test these to see if they still end up in the same category

Links:
http://fastml.com/converting-categorical-data-into-numbers-with-pandas-and-scikit-learn/
http://scikit-learn.org/stable/modules/feature_extraction.html#loading-features-from-dicts

Add key to dictionary:
http://stackoverflow.com/questions/1024847/add-key-to-a-dictionary-in-python

Count distinct words from a Pandas Data Frame
http://stackoverflow.com/questions/18936957/count-distinct-words-from-a-pandas-data-frame

How to vectorize a data frame with several text columns in scikit learn without losing track of the origin columns
http://stackoverflow.com/questions/30927610/how-to-vectorize-a-data-frame-with-several-text-columns-in-scikit-learn-without