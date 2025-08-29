# Converting-text-to-speech-by-processing-the-image
Text-to-image models turn written prompts into matching visuals by starting with random noise and refining it step by step. They work in a compressed latent space instead of raw pixels, making the process faster and more efficient.

Image Input – Users can upload or capture images containing printed or handwritten text (e.g., books, signboards, documents).

Text Extraction (OCR) – The system uses OCR technology (such as Tesseract OCR or EasyOCR) to detect and extract textual content from images.

Text Preprocessing – The extracted text is cleaned, formatted, and optimized for speech synthesis (removing noise, correcting errors).

Text-to-Speech Conversion – The processed text is converted into natural human-like speech using a TTS engine pyttsx3

Audio Output – saved as an audio file for offline listening
