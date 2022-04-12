# Visualization App on World Events

Making some cool maps about what is happening in Ukraine right now.

- Run Named Entity Recognition on GPU: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com//github/alexdseo/Visualization-App-on-World-Events/blob/master/NER.ipynb)

**#SupportUkraine**

## Workflow

[View Google Drive](https://drive.google.com/drive/folders/19LlSZPHSBr38YvoHUiRmO_9do4jt-lCX?usp=sharing)

### 1. Preprocess images

`image_preprocessing.ipynb`
- Requires: 
	- Pillow: `pip3 install PyMuPDF Pillow`
- Input: `data` (see Google Drive for all files; sample on GitHub)
- Output: `data_resized` (see Google Drive for all files; sample on GitHub)

### 2. Extract text with Optical Character Recognition

`text_extraction.ipynb`
- Requires:
	- Pillow: `pip3 install PyMuPDF Pillow`
	- PyTesseract: `pip install pytesseract`
	- Tesseract: `brew install tesseract`
- Input: `data_resized` (see Google Drive for all files; sample on GitHub)
- Output: `raw_text` (see Google Drive for all files; sample on GitHub)

### 3. Process text

`text_processing.ipynb`
- Input: `raw_text` (see Google Drive for all files; sample on GitHub)
- Output: `cleaned_text` (see Google Drive for all files; sample on GitHub)

### 4. Name Entities Recognition and analysis

### 5. Geolocation

### 6. Web page
