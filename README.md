# Hack the Valley 2024 Submission
# Won best Hack in the Diversity Theme Category
# Won best use of the frontend framework Streamlit

https://devpost.com/software/pitta-patta

# our why
Dialects, Lingoes, Creoles, Acrolects are more than just words, more than just languages - there are a means for cultural immersion, intangible pieces of tradition and history passed down through generations.

Remarkably two of the industry giants lag far behind - Google Translate doesn't support translations for the majority of dialects and ChatGPT's responses can be likened to a dog meowing or a cat barking.

Aiden grew up in Trinidad and Tobago, a native creole (patois) speaker; Nuween in Afghanistan making memories with his extended family in hazaragi, and Halle and Savvy though Canadian show their love and appreciation at home, in Cantonese and Mandarin, with their parents who are both 1st gen immigrants.

How can we bring dialect speakers and even non-dialect speakers alike together? How can we traverse cultures, when the infrastructure to do so isn’t up to par?


# pitta-patta, our solution
Pitta-Patta—an LLM-powered, voice-to-text web app designed to bridge cultural barriers and bring people together through language, no matter where they are.
With our innovative dialect translation system for underrepresented minorities, we enable users to seamlessly convert between standard English and dialects. 
Currently, we support Trinidadian Creole, Jamaican Patois and some Nigerian Pidgins as our proof of concept, with plans to expand further, championing a cause dear to all of us.


# Tech
Model: Our project is built on a Sequence-to-Sequence (Seq2Seq) model, tailored to translate Trinidadian Creole slang to English and back. 
The encoder compresses the input into a context vector, while the decoder generates the output sequence. We chose Long Short-Term Memory (LSTM) networks to handle the complexity of sequential data.

Frontend: The Front end was done using stream-lit.
