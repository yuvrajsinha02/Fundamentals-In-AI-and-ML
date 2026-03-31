## VITyarthi Project for Fundamentals Of AI and ML

# Student Details
**Name:** Yuvraj Sinha 

**Registration Number:** 25BCE11305

**Course:** B.Tech CSE Core  

**Course Code:** CSA    

**Institution:** VIT Bhopal University 

---

# Project Overfiew

This project is part of the VITyarthi Project for Fundamentals of AI and ML. It aims to create a language translator that can recognize any statement speoken in english and then asks for destination language and then translates and plays the translated audio

---

# Voice-to-Voice Language Translator
A Python-based, interactive voice translator that listens to spoken English, translates it into a target language of your choice, and speaks the translated text aloud.

This script utilizes Google's Speech Recognition to capture audio, the translate library to convert the text, and Google Text-to-Speech (gTTS) to generate the translated audio output.

# Features
- Speech-to-Text: Captures live audio from your default microphone.

- Multi-Language Support: Supports translation into dozens of languages (e.g., Hindi, Spanish, French, German, Japanese).

- Text-to-Speech: Automatically generates and plays an audio file of the translated text.

- Auto-Cleanup: Deletes the temporary audio file immediately after playing.

# Prerequisites
Before setting up the project, ensure you have the following installed on your system:

1. Python 3.7 or higher

2. A working microphone connected to your system.

---

# How to use 

- To use the translator, the user should have the following moules installed
1. playsound
2. speech recognition
3. translate
4. gtts
5. os

- Start the Script: Run the script in your terminal. You will see the prompt: listening.....

- Speak your phrase: Speak clearly into your microphone in English.

- Wait for Recognition: The console will display Recognizing..... and then print what it heard: The User said: [Your Phrase].

- Choose Target Language: The console will prompt you to enter the destination language (e.g., "Hindi", "Spanish", "French"). Speak the name of the language clearly into the microphone.

You can choose the destination language from the following list

Full Language List

```
Afrikaans

Albanian

Amharic

Arabic

Armenian

Assamese

Azerbaijani

Basque

Belarusian

Bengali

Bosnian

Bulgarian

Burmese

Catalan

Cebuano

Chichewa

Chinese

Corsican

Croatian

Czech

Danish

Dutch

English

Esperanto

Estonian

Filipino

Finnish

French

Frisian

Galician

Georgian

German

Greek

Gujarati

Haitian Creole

Hausa

Hawaiian

Hebrew

Hindi

Hmong

Hungarian

Icelandic

Igbo

Indonesian

Irish

Italian

Japanese

Javanese

Kannada

Kazakh

Khmer

Korean

Kurdish (Kurmanji)

Kyrgyz

Lao

Latin

Latvian

Lithuanian

Luxembourgish

Macedonian

Malagasy

Malay

Malayalam

Maltese

Maori

Marathi

Mongolian

Myanmar

Nepali

Norwegian

Odia

Pashto

Persian

Polish

Portuguese

Punjabi

Romanian

Russian

Samoan

Scots Gaelic

Serbian

Sesotho

Shona

Sindhi

Sinhala

Slovak

Slovenian

Somali

Spanish

Sundanese

Swahili

Swedish

Tajik

Tamil

Telugu

Tibetan

Thai

Turkish

Ukrainian

Urdu

Uyghur

Uzbek

Vietnamese

Welsh

Xhosa

Yiddish

Yoruba

Zulu
```
- Listen and Read: The script will fetch the translation, play it aloud through your speakers, and print the translated text in the console.
