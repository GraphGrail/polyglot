GraphGrail Ai – is the world’s first Artificial Intelligence platform for Blockchain built on top of Natural Language Understanding technology with the DApps marketplace

Algorithms:
1. Word Embeddings
Word embedding is a mapping of a word to a d-dimensional vector space. This real valued vector representation captures semantic and syntactic features. Polyglot offers a simple interface to load several formats of word embeddings.
Formats
The Embedding class can read word embeddings from different sources:
Gensim word2vec objects: (from_gensim method)
Word2vec binary/text models: (from_word2vec method)
GloVe models (from_glove method)
polyglot pickle files: (load method)

2. Part of Speech Tagging
Part of speech tagging task aims to assign every word/token in plain text a category that identifies the syntactic functionality of the word occurrence.
Polyglot recognizes 17 parts of speech, this set is called the universal part of speech tag set:
ADJ: adjective
ADP: adposition
ADV: adverb
AUX: auxiliary verb
CONJ: coordinating conjunction
DET: determiner
INTJ: interjection
NOUN: noun
NUM: numeral
PART: particle
PRON: pronoun
PROPN: proper noun
PUNCT: punctuation
SCONJ: subordinating conjunction
SYM: symbol
VERB: verb
X: other

3. Named Entity Extraction
Named entity extraction task aims to extract phrases from plain text that correpond to entities. Polyglot recognizes 3 categories of entities:
Locations (Tag: I-LOC): cities, countries, regions, continents, neighborhoods, administrative divisions …
Organizations (Tag: I-ORG): sports teams, newspapers, banks, universities, schools, non-profits, companies, …
Persons (Tag: I-PER): politicians, scientists, artists, atheletes …


4. Morphological Analysis

Languages Coverage
Using polyglot vocabulary dictionaries, we trained morfessor models on the most frequent words 50,000 words of each language.
from polyglot.downloader import downloader
print(downloader.supported_languages_table("morph2"))
1. Piedmontese language       2. Lombard language           3. Gan Chinese
 4. Sicilian                   5. Scots                      6. Kirghiz, Kyrgyz
 7. Pashto, Pushto             8. Kurdish                    9. Portuguese
10. Kannada                   11. Korean                    12. Khmer
13. Kazakh                    14. Ilokano                   15. Polish
16. Panjabi, Punjabi          17. Georgian                  18. Chuvash
19. Alemannic                 20. Czech                     21. Welsh
22. Chechen                   23. Catalan; Valencian        24. Northern Sami
25. Sanskrit (Saṁskṛta)       26. Slovene                   27. Javanese
28. Slovak                    29. Bosnian-Croatian-Serbian  30. Bavarian
31. Swedish                   32. Swahili                   33. Sundanese
34. Serbian                   35. Albanian                  36. Japanese
37. Western Frisian           38. French                    39. Finnish
40. Upper Sorbian             41. Faroese                   42. Persian
43. Sinhala, Sinhalese        44. Italian                   45. Amharic
46. Aragonese                 47. Volapük                   48. Icelandic
49. Sakha                     50. Afrikaans                 51. Indonesian
52. Interlingua               53. Azerbaijani               54. Ido
55. Arabic                    56. Assamese                  57. Yoruba
58. Yiddish                   59. Waray-Waray               60. Croatian
61. Hungarian                 62. Haitian; Haitian Creole   63. Quechua
64. Armenian                  65. Hebrew (modern)           66. Silesian
67. Hindi                     68. Divehi; Dhivehi; Mald...  69. German
70. Danish                    71. Occitan                   72. Tagalog
73. Turkmen                   74. Thai                      75. Tajik
76. Greek, Modern             77. Telugu                    78. Tamil
79. Oriya                     80. Ossetian, Ossetic         81. Tatar
82. Turkish                   83. Kapampangan               84. Venetian
85. Manx                      86. Gujarati                  87. Galician
88. Irish                     89. Scottish Gaelic; Gaelic   90. Nepali
91. Cebuano                   92. Zazaki                    93. Walloon
94. Dutch                     95. Norwegian                 96. Norwegian Nynorsk
97. West Flemish              98. Chinese                   99. Bosnian
100. Breton                   101. Belarusian               102. Bulgarian
103. Bashkir                  104. Egyptian Arabic          105. Tibetan Standard, Tib...
106. Bengali                  107. Burmese                  108. Romansh
109. Marathi (Marāṭhī)        110. Malay                    111. Maltese
112. Russian                  113. Macedonian               114. Malayalam
115. Mongolian                116. Malagasy                 117. Vietnamese
118. Spanish; Castilian       119. Estonian                 120. Basque
121. Bishnupriya Manipuri     122. Asturian                 123. English
124. Esperanto                125. Luxembourgish, Letzeb... 126. Latin
127. Uighur, Uyghur           128. Ukrainian                129. Limburgish, Limburgan...
130. Latvian                  131. Urdu                     132. Lithuanian
133. Fiji Hindi               134. Uzbek                    135. Romanian, Moldavian, ...


This module is not belong to Graph Grail!!!
It will be used to integrate with the micro services provided by Graph Grail.
