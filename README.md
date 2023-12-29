# NLU-Tasks

+ This trial consists in solving the provided NLU tasks. With respect to task1, I extended the Java Speech Grammar Format (JSGF) grammars for music play intent recognition. The English grammar was expanded to cover additional utterances such as expressing a desire to listen to jazz or requesting a specific album by an artist. Moreover, the Arabic, French, and Spanish grammars were similarly extended to encompass a variety of music-related requests, incorporating diverse artists, songs, genres, and albums. 
  
+ For the localization task, I tailored the grammars to the linguistic and cultural nuances of Arabic, French, and Spanish. The grammars were adapted to handle diverse named entities relevant to each language, including artists, songs, genres, and albums. Sample utterances were provided to showcase the grammars in action, ensuring a comprehensive coverage of music-related requests in both languages.

+ Regarding Arabic, given the divergence in orthography compared to other languages, my approach involved transliterating elements that closely align with their pronunciation in the original language. In instances where there might be variations in pronunciation, I retained the names of songs and artists in their original language to preserve authenticity.

+ In general, utterances may face challenges in grammatical completeness and semantic correctness if we solely depend on the provided grammar. As a remedy, I recommend incorporating new tags to encompass both semantic and lexical language levels, ensuring a more comprehensive and linguistically accurate representation.

+ To enhance the model's ability to grasp the meaning of user utterances, I propose extending the code by integrating new tags that encompass missing elements, particularly Parts-of-Speech (POS) tags. This augmentation aims to provide a more comprehensive linguistic framework, thereby improving the model's accuracy in understanding and interpreting diverse expressions.
  
