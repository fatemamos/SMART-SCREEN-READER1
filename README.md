# SMART-SCREEN-READER
Smart Screen Reader 
Overview
The Smart Screen Reader is an Android application designed to assist visually impaired users by converting text from images into speech. It uses a combination of advanced technologies like OpenCV for image processing, Firebase ML for text recognition, and Google Cloud Translate for language translation. This app allows users to interact with printed or handwritten text by simply taking a picture, which the app processes to read aloud or translate the content.

Features
Text Recognition: Captures images and extracts text using machine learning models provided by Firebase ML.
Text-to-Speech (TTS): Converts the recognized text into speech, allowing users to hear the content. The app supports multiple languages, including English, Arabic, and Hebrew.
Template Matching: Uses computer vision techniques to identify and highlight specific words or patterns within the captured image.
Barcode Scanning: Detects and decodes various types of barcodes, providing relevant information or actions based on the scanned content.
Translation: Translates recognized text into the user’s preferred language using Google Cloud Translate services.
Navigation: Allows users to navigate through recognized text using mouse gestures, with real-time feedback on the location and content of the text.
Installation and Setup
To set up the Smart Screen Reader, follow these steps:

Clone the Project: Download the source code from the repository.
Configure Firebase: Integrate Firebase by adding your Firebase configuration file and enabling the necessary services like Firebase ML.
Add Google API Key: Set up Google Cloud Translate by adding your API key to the app.
Integrate OpenCV: Ensure OpenCV is properly integrated into the project for image processing capabilities.
Set Permissions: The app requires permissions for camera access and storage to capture and save images.
How to Use
Capture an Image: Users can take a picture of any printed or handwritten text using their device's camera. The app then processes the image to extract the text.
Text Navigation: Once the text is recognized, users can navigate through it using mouse gestures. The app provides audio feedback to help locate specific words.
Translation: Users can choose to translate the recognized text into another language. The translated text is then read aloud in the selected language.
Barcode Scanning: The app can also detect barcodes within the image and provide relevant information or actions based on the type of barcode.
Save and Share: Users can save the recognized or translated text for future use or share it through other apps.
Customization
Adding More Languages: The app currently supports English, Arabic, and Hebrew. Additional languages can be added by modifying the settings in the language selection and translation features.
Template Matching: Users can customize the template matching feature by adding new templates, allowing the app to recognize specific patterns or objects in images.
Contribution
If you would like to contribute to the project, you can fork the repository, create a new branch, make your changes, and submit a pull request for review.

Acknowledgments
OpenCV: For the powerful image processing capabilities.
Firebase ML: For enabling advanced text recognition and barcode scanning.
Google Cloud Translate: For the translation services integrated into the app.
Android Development Community: For the support and resources that helped in developing this application.
