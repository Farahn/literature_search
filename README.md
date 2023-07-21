# Literature Search

Automate literature search using Semantic Scholar and basic text processing.

This IPython Notebook uses the Semantic Scholar API to automatically search for research papers given search term(s), field(s) of study, and the year range. 

The information is parsed into a Pandas DataFrame, followed by some basic title and abstract columns cleanup. We then add flags to the DataFrame based on string matches in the title or abstract to make it easier to search within the file.
