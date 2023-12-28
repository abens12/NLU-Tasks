# NLU-Tasks

+ This trial consists in solving the provided NLU tasks. With respect to task1, I extended the Java Speech Grammar Format (JSGF) grammars for music play intent recognition. The English grammar was expanded to cover additional utterances such as expressing a desire to listen to jazz or requesting a specific album by an artist. Moreover, the Arabic, French, and Spanish grammars were similarly extended to encompass a variety of music-related requests, incorporating diverse artists, songs, genres, and albums. 
  
+ For the localization task, I tailored the grammars to the linguistic and cultural nuances of Arabic, French, and Spanish. The grammars were adapted to handle diverse named entities relevant to each language, including artists, songs, genres, and albums. Sample utterances were provided to showcase the grammars in action, ensuring a comprehensive coverage of music-related requests in both languages.

+ with respect to Arabic, as its orthography differs from the other languages, i attempted to transliterate whatever could be pronounced similar to the original language. should any difference in the pronounciation araises, songs and artists are mantained as they are in original language.

+ Generally, utterances could suffer from the lack of POS tags if we rely on the provided grammar. Thus, sentences could sound grammarly uncomplete and therefore semantically uncorrect. I would suggest including new tags for covering semantic and lexical language levels.

  
