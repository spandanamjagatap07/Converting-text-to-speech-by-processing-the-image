## Image to Text to Speech Converter

This project extracts text from an image using **Optical Character Recognition (OCR)** and converts the extracted text into **speech audio**.

### Project Overview

* The program reads an image containing text.
* It uses **Tesseract OCR** to extract text from the image.
* The extracted text is then converted into **speech** using **Google Text-to-Speech (gTTS)**.
* The generated speech is saved as an **MP3 audio file**.

### Technologies Used

* **Python**
* **Pillow (PIL)** – for image processing
* **pytesseract** – for Optical Character Recognition (OCR)
* **gTTS (Google Text-to-Speech)** – for converting text into speech

### Working Flow

1. Load the input image using **PIL**.
2. Apply **pytesseract OCR** to extract text from the image.
3. Check if text is detected.
4. Convert the extracted text into speech using **gTTS**.
5. Save the speech output as an **MP3 audio file**.

### Functions in the Code

* **image_to_text()**
  Extracts text from the given image using Tesseract OCR.

* **text_to_speech()**
  Converts the extracted text into speech and saves it as an audio file.

* **main()**
  Controls the workflow by calling the OCR function and the text-to-speech function.

### Output

* Extracted text is printed in the terminal.
* Speech audio file is generated and saved as **`output_speech.mp3`**.

### Use Cases

* Assistive technology for **visually impaired users**
* Reading **documents or printed text from images**
* **Educational tools** for text recognition and speech synthesis
