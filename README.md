# Summary

A Universal Dependencies corpus for Ika, a member of the Chibchan language family. The language is spoken by about 25,000 speakers in Colombia.

# Introduction

The treebank is an automatic conversion of complete trees of the SUD_Ika-ChibErgIS, which is an automatic conversion of the [mSUD_Ika-ChibErgIS](https://github.com/surfacesyntacticud/mSUD_Ika-ChibErgIS) which was extracted from an interlinearized corpus in Flex format.

The original corpus consists of 40 texts recorded in the Ika language (41 recordings). The texts were collected as part of original fieldwork conducted between 2018 and 2022 in Pueblo Bello, Cesar, Colombia.



# Annotation Metadata

Sentences are annotated with the following metadata:
 - `speaker_id` (which identifies the turn of speech)
 - `sent_timecode` (which will enable playback of the sentence)
 - `morphemic_text`: (original segmentation of the text into morphemes)
 - `text`: (lexical tokenization)
 - `text_en`: (English interpretation)
 - `text_phrase-gls-de`: (original id)
 - `text_phrase-gls-es`: (Spanish interpretation)
 - `text_phrase-gls-tl`: (original comments in Flex)


# Structure
This version of the treebank is a dependency parsing of the original corpus first complete trees.

The original data are spoken data, which were originally segmented in words and interlinearized and glossed in Flex with concatenated clitics. Tokens comprize words and affixes (preceded by a "=" sign). 

The corpus structure was designed by Stavros Skopeteas and comprises four different text types: spoken narratives (ancestor stories; AN), retellings of the Pear Story (PE), procedural texts (instructions for preparing a meal; CO), and comparative descriptions (contrasting the Ika people with other indigenous communities; CD). The labelling scheme, also developed by Stavros Skopeteas, follows a structured format to ensure that each text is uniquely identifiable and provides clear metadata for organisation. The format is as follows:

language-collection-instruction-00000-speaker

This label consists of the following components:

ARH: the language identifier, representing Ika in this corpus.
TXT: indicates the "Texts" subcollection, showing that the recording belongs to the textual part of the corpus.
AN, TS, CD, or PE: specify the type of recording.
00000: a placeholder component that has no functional role in this subcollection.
The final number identifies the speaker, corresponding to a specific individual.



The **UD_IKA-ChibErgIS** counts NUMBER tokens for NUMBER sentences.

# References

(none available yet)

# Acknowledgments

This treebank was produced as part of the ChibErgIS project. With special thanks to Bruno Guillaume for the conversion from SUD to UD, Sylvain Kahane, WHO ELSE?. Also special thanks to Natalia Cáceres Arandia for help with the (S)UD-annotation and to Florian Deichsler for help with glossing in Flex and solving all kinds of problems.

# Changelog

* 2025-05-15 v2.16
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.16
License: CC BY-SA 4.0
Includes text: yes
Genre: spoken
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Bajorat, Jana
Contributing: here
Contact: jana.bajorat@hu-berlin.de
===============================================================================
</pre>
