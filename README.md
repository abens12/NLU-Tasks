# NLU-Tasks

+ This trial consists in solving the provided NLU tasks. With respect to task1, I extended the Java Speech Grammar Format (JSGF) grammars for music play intent recognition. The English grammar was expanded to cover additional utterances such as expressing a desire to listen to jazz or requesting a specific album by an artist. Moreover, The Arabic,French, and Spanish grammars were similarly extended to encompass a variety of music-related requests, incorporating diverse artists, songs, genres, and albums in the alreasdy mentioned languages. 
  
+For localization, I tailored the grammars to the linguistic and cultural nuances of Arabic, French, and Spanish. The grammars were adapted to handle diverse named entities relevant to each language, including artists, songs, genres, and albums. Sample utterances were provided to showcase the grammars in action, ensuring a comprehensive coverage of music-related requests in both languages.
  

# Task1: English grammar Extention

+ in order to extend the english grammar, as shown in the example provided in the pdf documentation, tags such as <genre> and <album> should be added right after the intent. In addition, the same tags must include entities for the parsing process. In this manner, the english extended grammar should be as such:

#JSGF V1.0 utf-8 en;

grammar music_play;

public <music_play> =
  [can you] (put on | play) (<artist> | <song> | <genre> | <album>);
<artist> =
  the beatles |
  radiohead |
  lady gaga |
  pink floyd;
<song> =
  comfortably numb |
  paranoid android |
  let it be |
  hey jude;
<genre> =
  jazz |
  rock |
  pop;
<album> =
  ummagumma;





