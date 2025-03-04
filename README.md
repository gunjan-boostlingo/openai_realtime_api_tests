Reimplementation of OpenAI Realtime API tutorial from https://www.datacamp.com/tutorial/realtime-api-openai

Thoughts on OpenAI's speech-to-speech capabilities for translation:
- Overall, very capable and for most practical applications, easily beats out a cascaded speech-to-text, translation, and text-to-speech system. I tried translating meeting summaries, current event news, and conversational dialogue to Spanish, French, Hindi, Nepali, and Urdu, and all of them performed quite well.
- The model is very quick. It only takes about a second before the model begins to respond/translate
- For specialized cases, there is likely room to improve. I tested out some esoteric Urdu poetry in a moderate American English accent, and it ranged from "spot on" to "sort of there". Still, what the Realtime API offered was significantly better than almost any translation offered by native speakers online.
- Text-to-speech voices sound fairly natural (though for Nepali, there seems to be a bit of American English influence)
