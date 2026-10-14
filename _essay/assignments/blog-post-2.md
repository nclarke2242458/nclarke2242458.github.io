---
title: DH in Practice
order: 2
part: Blog
---
**DH in Practice** 

You can't experience the Irish Gothic mode in fiction without reading it as a cultural and political product. It's ingrained in character and action, down to the very words.

Existing research focuses on some of Ireland's most brilliant manipulators of the tradition, but only a select few appear in larger-scale projects. For a long time, financial, archival, and technological constraints kept those projects small. Digital humanities tools have changed so much over the last ten years that tracing the Irish Gothic's word-choice patterns across many stories is now possible.

My research looks at how Irish Gothic short fiction portrays monsters, and at how an author's religious identity, and the place of that identity in Irish society and political life, shaped their writing. Scholars of the Irish Gothic, particularly Dr. Jarlath Killeen, have interpreted the genre as an Anglican mode of writing, which could leave it limited to Anglican authors.  
My project dips its toes into that conversation by asking a smaller question: do Irish Gothic writers from religious minorities describe monsters with different vocabulary or sentiment than canonical Anglo-Irish authors? Answering it calls for recovering lesser-known writers, and readings of the Irish Gothic that have been pushed aside in favor of whatever is most widely available. Even counting only periodical publications from a little before to a little after the nineteenth century, and keeping in mind that most of these stories appeared unattributed, my list includes big and small names alike: Elizabeth Griffith, Anna Millikin, Charles Robert Maturin, John and Michael Banim, William Carleton, Joseph Sheridan Le Fanu, Fitz-James O'Brien, Rosa Mulholland, Bram Stoker, Charlotte Riddell, Oscar Wilde, B. M. Croker, L. T. Meade, Ethna Carbery, and Beatrice Grimshaw.

I plan to use Python's Natural Language Toolkit (NLTK) and RStudio for word frequency, sentiment analysis, and topic modeling. Together, they let me put 60 to 80 stories in conversation at once, certainly more than I can hold in my head. All of this depends on optical character recognition (OCR). My corpus comes from digitized periodicals and short story collections, and nineteenth-century print does not always survive the trip. A frequency count would treat reading errors as new words, so cleaning the text must be part of the method. Standard sentiment tools have a second problem: they are built on modern English. VADER, the sentiment tool that comes with NLTK, was designed for social media text (Hutto and Gilbert 2014). In the nineteenth century, "awful" could still mean awe-inspiring, and a modern lexicon will score it as simply negative. So I am building a sentiment dictionary from nineteenth-century dictionaries, so the scores reflect what words meant to the people who wrote and read these stories. I am also wary of large-scale analysis replacing close reading. I plan to move between the two. 

The 60 to 80 stories are a small, experimental test. If the method holds up, I have a collection of about 250 to 300 texts ready for a larger project, which would show whether the patterns hold across the whole list.

Hutto, C. J., and Eric Gilbert. 2014\. “VADER: A Parsimonious Rule-Based Model for Sentiment Analysis of Social Media Text.” *Proceedings of the International AAAI Conference on Web and Social Media* 8 (1): 216–25. [https\://doi.org/10.1609/icwsm.v8i1.14550](https://doi.org/10.1609/icwsm.v8i1.14550).

Killeen, Jarlath. 2014\. *The Emergence of Irish Gothic Fiction: Histories, Origins, Theories*. Edinburgh: Edinburgh University Press.  

Moretti, Franco. *Distant Reading*. Verso, 2015\.
