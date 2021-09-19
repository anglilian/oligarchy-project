# Oligarchy Project

## Image Preprocessing
- Binarise images
- Crop images into single columned text
- Correct Skew

## Extract Text
- OCR with AWS Textract (yielded better results than Tesseract). 
- Correct OCR mistakes with SpellChecker
- Split text into sections based on each person's name
- Categorise information based on keywords and patterns

## Build Network
- Group similar locations or institutions
- Map connections between nodes based on number of shared affiliations
- Draw network using Gephi
