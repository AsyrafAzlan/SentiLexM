# SentiLexM
Malay and English lexicon for solving sentiment analysis tasks.

SentiLexM.txt was created in 2015 as part of the work in the following publication:
</br>[1] Tan, Yi-Fei, Hai-Shuan Lam, Asyraf Azlan, and Wooi-King Soo. "Sentiment Analysis for Telco Popularity on Twitter Big Data Using a Novel Malaysian Dictionary." In *ICADIWT*, pp. 112-125. 2016.

SentiLexM was derived from its original English version called AFINN-111 by:
</br>[2] Finn Årup Nielsen, “AFINN”, Last visited: 31 August 2015. (http://www2.imm.dtu.dk/pubdb/views/publication_details.php?id=6010)

The Malay words were translated based on:
</br>[3] Dewan Bahasa dan Pustaka. 1st Ed. "*Kamus Dewan Inggeris Melayu – An English-Malay Dictionary.*" Kuala Lumpur: Dewan Bahasa dan Pustaka, Malaysian Ministry of Education. 1992.

I am uploading this in hopes that it may be beneficial (and perhaps improved) by the community.

Properties of SentiLexM are as follows:
</br>•	26,004 words: 2477 English, 23,527 Malay.
</br>•	The sentiment scores ranges between +5 and -5.
</br>•	All words are lowercased.
</br>•	SentiLexM itself not language sensitive, new words can be added in the dictionary.  Malay words start immediately after the last English word.
</br>•	The English words are sorted according to their alphabets (i.e. from ‘a’ to ‘z’), however, the Malay translation is not sorted alphabetically but rather sorted according to the English entry.
</br>•	The scoring of the Malay sentiment words strictly follow the scoring of the original English words. e.g. 'abandon' = -2 and 'mengabaikan' = -2.
</br>•	Includes Malay slang words/translations.
</br>•	The method of translation includes every possible version of the Malay verb.  E.g. the English word ‘slow’ translates to ‘lambat’ in Malay, which is the root word.  Despite that, the translation attempted to incorporate other versions of the word including past, present, future, or other forms of a word such as adverb, adjective, noun and more.  In order to include all of these variations of Malay words, a number of prefixes and suffixes have been identified and they are to be added to each root Malay words if the word exist in a dictionary or real-life application.  Table 1 shows the list of the prefixes and suffixes that make up various forms of Malay words while Table 2 shows the application of this method of translation and how one English word may translate to approximately 20 Malay words.

![alt text](https://github.com/AsyrafAzlan/SentiLexM/blob/main/translation-method.PNG?raw=true)
