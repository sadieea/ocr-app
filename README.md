# ocr-app
Optical Character Recognition (Text Extraction from images)

Overview
This project is a web-based prototype that implements Optical Character Recognition (OCR) to extract text from uploaded images containing text in both Hindi and English. It features a basic keyword search functionality, allowing users to search the extracted text. The application is accessible online via a live URL.
Objective
To develop and deploy a web-based application that performs OCR on images and allows keyword searching within the extracted text. The prototype should be live and accessible via a public URL.
URL- https://huggingface.co/spaces/sadieea/ocr-app
Technologies Used
•	Python: The programming language used for development.
•	EasyOCR: An OCR library to extract text from images.
•	Gradio: A library for creating interactive web interfaces.
•	Pillow: An image processing library for handling image files.
Usage
1.	Open a web browser and navigate to the URL provided after running the application.
2.	Click the "Upload Image" button to select an image file containing text.
3.	The application will display the extracted text after processing the image.
4.	Enter keywords in the search box and click the "Search" button. Matching sections will be highlighted.
Features
•	Image Upload: Users can upload images in formats such as JPEG and PNG.
•	Text Extraction: Extracts text from uploaded images using EasyOCR.
•	Keyword Search: Allows users to search for keywords within the extracted text, highlighting matches.
•	Multi-language Support: Supports extraction of text in both Hindi and English.
Deployment
The application is deployed on Hugging Face Spaces. Users can access it via the provided live URL.
Testing
The application was tested with various images that included:
•	Clear text
•	Blurry text
•	Text in both Hindi and English
Troubleshooting
•	Issue: Application fails to run.
o	Solution: Ensure all dependencies are installed and verify that you are in the correct directory.
•	Issue: No text is extracted from images.
o	Solution: Check the quality of the image. Blurry images may lead to poor results.
•	Issue: Search functionality does not highlight keywords.
o	Solution: Verify that the text extraction was successful and that the keywords exist in the extracted text.
Assumptions
•	The OCR model used (EasyOCR) will effectively handle both Hindi and English text extraction.
•	The web application will function correctly across modern web browsers.
