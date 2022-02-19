# Trie-Trees-and-Autocomplete-Bots

I use an amalgamation of classes, objects, and texts to create a trie class (i.e., prefix tree) which stores words within a text based on prefixes and provides easy searching and returning capabilities for precise words with minimized time complexity. Moreover, I provide an autocomplete method within each instance of a trie that autocompletes words when provided prefixes that match the initial elements of words within the text. For the code below, any uploaded text can be traversed to determine the presence of a prefix, word, or the number of recurrences of a word within the provided text.

# My Prefix Tree Portrayal in Python

My trie tree uses a combination of nodes (i.e., where each individual node is specified in a separate instance of the Node class) to store a set of strings in the nodes' collection. The separate Trie class contains the prefix tree and the following methods: 

- insert(self, word): allows the user to insert a word into the trie and creates the necessary new nodes for new prefixes while the word is being added to the entire trie.
- lookup(self, word): provides the capability to search for a prefix or word within the specified trie and returns the appropriate boolean value indicator.
- preorder(self, root, lst): sorts the specified trie using preorder traversal which processes each parent node prior to processing its corresponding child nodes.
- alphabetical_list(self): provides the user the capability to return the contents of the trie in alphabetical order.
- k_most_common(self, k): finds the k-most common words in a trie using preorder traversal.
- autocomplete(self, prefix): finds the most common word from the provided text with the provided prefix.

I hope you enjoy the code! Thank you for stopping by :)
