# AutoSuggestusingTrie
Implemented the auto suggest feature used in browsers to suggest the words from incomplete written words by the user.
Stored 15,000 most used words in English inTrie data structure.
The autosuggest function returns all the strings having the given prefix, if the given prefix does not exist it return the input string.
The trie prefix search is about 26.7 times faster than normal prefix search. Also the memory required to store the words is very less as compared to storing as a list of strings.
