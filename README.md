# NLP-Norvig-spell-corrector
This project builds a Norvig spell corrector, which is an elementary yet powerful spell correction method that finds out probable correct spellings by finding out words one or two or multiple edit distance away.

# Norvig spell correction algorithm
The Norvig spell corrector algorithm takes an input word whose spelling has to be checked, finds out a list of all similar words that are one edit distance away or two edit distances away and so on, and finds out the probability of occurence of each of these words based on a training corpus. Finally, the similar word with the highest probability of occurence is chosen as the correct spelling. 
If the given word however already exists in the training corpus, then no spelling correction is required.

