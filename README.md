# Music-Generation-App
Hugging face generative IA project
Music Generation App
This Music Generation App allows users to create beautiful, AI-generated music based on text prompts. Powered by advanced models, the app generates a variety of music experiences ranging from serene piano compositions to more complex musical journeys, all in real time.

Features
Text-to-Music Generation: simply input a text prompt, and the app will generate a unique piece of music that reflects the mood and themes of your description.

Customizable Prompts: customize the music generation with your own words. For example, describe the mood, instruments, or setting for the music.

High-Quality Audio: the app generates high-quality audio with a length of up to 10.24 seconds, perfect for small musical snippets or background sounds.

How to Use
Input a Prompt: type a text description of the music you want to generate. Example prompts could be:

"A serene and elegant piano composition, evoking a sense of royal grandeur."

"A peaceful forest melody with light strings and a gentle piano."

Generate Music: click the "Generate" button to generate a music track based on the provided prompt. The app will return a unique piece of music that matches your description.

Listen and Enjoy: the generated music will be available as audio for you to listen to directly in the app.

Technical Details
The app uses Gradio to create an interactive web interface for easy music generation.

It uses an audio generation pipeline powered by an AI model, which synthesizes music based on the given text prompt.

The app generates audio at 16 kHz sample rate with a duration of 10.24 seconds.

Requirements
To run the app locally, you’ll need the following dependencies:

Python (3.7 or higher)

Gradio for creating the user interface

Torch (PyTorch) for the deep learning model

Diffusers library for the AI model that generates audio

Install the necessary packages with:
```
pip install gradio torch diffusers
```
Example Prompts
Here are some example prompts to try:

"A serene and elegant piano composition, evoking a sense of royal grandeur."

"A lighthearted ukulele strumming in a beachside jam."

"A dark and brooding orchestral piece with deep strings and haunting melodies."

