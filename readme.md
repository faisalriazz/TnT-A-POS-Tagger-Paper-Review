# TnT, the short form of Trigrams'n'Tags, 
is a very efficient statistical part-of-speech tagger that is trainable on different languages and virtually any tagset. 
The component for parameter generation trains on tagged corpora. The system incorporates several methods of smoothing and 
of handling unknown words.
TnT is not optimized for a particular language. Instead, it is optimized for training on a large variety of corpora. 
Adapting the tagger to a new language, new domain, or new tagset is very easy. Additionally, TnT is optimized for speed.
The tagger is an implementation of the Viterbi algorithm for second order Markov models. 
The main paradigm used for smoothing is linear interpolation, the respective weights are determined by deleted interpolation.
Unknown words are handled by a suffix trie and successive abstraction.

## Repository 
Includes the Review of Paper Presented by Thorsten Brants in 2000, "TnT A statistical part-of-speech tagger". 
Presentation of the Review and original paper as well. 

