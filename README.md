[\[English\]](#Introduction) [\[Português\]](READMEP.md)
_______________________________________________________________________________________________________________________________________
## Introduction
We tested some of the related services in [Azure Speech Studio](https://speech.microsoft.com/) and [Azure Language Studio](https://language.cognitive.azure.com/). Some text and audio were used to generate the result according to the tables shown in each functionality test.

## Speech to Text on Speech Studio

Using [Azure Speech Studio](https://speech.microsoft.com/), quickly test your audio on a speech recognition endpoint without writing any code. The audio will be transformed into text. You can choose the language of the input audio.

| Audio                                      | Result                                 | JSON                                    |
|---------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| [Audio](Input/WhatAICanDo.m4a) | AI enables us to build amazing software that can improve healthcare, enable people to overcome physical disadvantages. Empower smart infrastructure, create incredible entertainment experiences, and even save the planet.<br><br> [File](Output/WhatAICanDo.txt) | [JSON](Output/WhatAICanDo.json) |

## Analyze Sentiment and Opinions on Language Studio

Using [Azure Language Studio](https://language.cognitive.azure.com/) and the Text Analytics API's Sentiment Analysis feature, which provides sentiment labels (such as "negative", "neutral" and "positive") and confidence scores at the sentence and document-level. You can also send Opinion Mining requests using the Sentiment Analysis endpoint, which provides granular information about the opinions related to words (such as the attributes of products or services) in the text.

| Text                                      | Result                                 | JSON                                    |
|---------------------------------------------|-----------------------------------------------|-----------------------------------------------|
| [Text](Input/Opinion1.txt) | ![Image](Output/ASOpinion1.jpg)<br>![Image](Output/Sentence1Opinion1.jpg)<br>![Image](Output/Sentence2Opinion1.jpg)<br>![Image](Output/Sentence3Opinion1.jpg)<br>![Image](Output/OriginalTextOpinion1.jpg)<br> | [JSON](Output/ResultOpinion1.json) |

## References

[Explore Speech Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)

[Analyze text with Language Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)
