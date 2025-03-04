Reimplementation of OpenAI Realtime API tutorial from https://www.datacamp.com/tutorial/realtime-api-openai

Thoughts on OpenAI's speech-to-speech capabilities for translation:
- Overall, very capable and for most practical applications, easily beats out a cascaded speech-to-text, translation, and text-to-speech system. I tried translating meeting summaries, current event news, and conversational dialogue to Spanish, French, Hindi, Nepali, and Urdu, and all of them performed quite well.
- The model is very quick. It only takes about a second before the model begins to respond/translate
- For specialized cases, there is likely room to improve. I tested out some esoteric Urdu poetry in a moderate American English accent, and it ranged from "spot on" to "sort of there". Still, what the Realtime API offered was significantly better than almost any translation offered by native speakers online.
- Text-to-speech voices sound fairly natural (though for Nepali, there seems to be a bit of American English influence)

Overall, I found the Realtime API's speech-to-speech capabilities to probably beat out the majority of laypeople in being able to translate, though perhaps not those specialized in translating or teaching a language (for instance, in the English to Hindi translation tests, the model seemed to did better than most bilingual English/Hindi speakers but would probably be slightly beaten out by my college Hindi professor - though it probably would be faster than her in giving out that translation). Further work should be done to test the value of this model.
