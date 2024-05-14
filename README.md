# Philosopher extractor from Google's suggestions

The project extracts relationships between any name given as input and the names suggested by Google when searching for an alternative to something, i.e., the suggestions that would appear in the search bar by typing “[name] vs. ...” The purpose of the project is to get a ranking of the most influential philosophers in history, but the program can be applied to anything, as long as you want to compare alternatives in the same field (brands, programs, programming languages, ideologies, etc.).

Tools used:
- xml.etree.ElementTree
- networkx
- matplotlib
- urllib3
- pandas
- pyvis
