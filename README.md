# OCR-Recognition

## Form recognition with Microsoft azure services
SBI FORM RECOGNITION
Azure Form Recognizer is an api service that is used to build automated data processing and recognition using machine learning technology. Identify and extract text, key/value pairs, selection marks (Checkboxes), tables, and structure from given documents—the service outputs structured data that includes the relationships in the original file, bounding boxes, confidence and more. 

Approach- 
Microsoft azure form recognizer REST APIs ,Version : V2.1-preview.2
Used free tier - 500 transactions /month
Preferred location for storage account / resource group : East US
Microsoft Azure account : Educational account tiered with Github 
1. The following APIs to train models and extract structured data from forms:
 
Name | Description
---- | -----------
Train Custom Model | Train a (custom) new model to analyze SBI forms by using three forms of the same type. Set the useLabelFile parameter to false to and includeSubFolders to true .
Analyze Form | Analyze a form passed in as a stream to extract text, key/value pairs, checkboxes and tables from the form with the custom model.
 
2. Form Recognizer works on input documents that meet these requirements:
Format must be JPG, PNG, PDF (text or scanned), or TIFF. Text-embedded PDFs are best because there's no possibility of error in character extraction and location.
3. Quick overview of the process-
Simple extraction-Easily pull data and organize information with prebuilt and custom features.
Customized results- Get output tailored to your layouts with automatic custom extraction, and improve it with human feedback.
Built-in security-Rely on security and privacy applied to both your data and any trained models.

## Preferred Microsoft azure form recognition
The following features are supported by Microsoft and made available to be one of the efficient and optimal services to build custom models and perform custom OCR form recognition.
Built Custom model with customized forms which majorly involves Create intelligent search indexes which specifies data processing and data extraction to save time and cost and performance.
Training data - 
Minimum files - 5 sample input
Training speed - 15 transactions per second
Enhanced table extraction - Form Recognizer  provides enhanced table extraction, which combines featurized Optical Character Recognition (OCR) capabilities which can extract data from tables, including complex tables with merged columns, rows, no borders and more.
Language support for Form Recognizer- It supports 9 languages during form recognition.
Text line style indication (handwritten/other) (English)- Form Recognizer now outputs an appearance object classifying whether each text line is handwritten style or not, along with a confidence score.
Privacy and Security - Form Recognizer keeps your data private. The custom training performed on your documents is not used by Microsoft to improve the Form Recognizer model.

FORM RECOGNITION RESULTS-
After performing the form recognition using REST API , the service provides output which identifies and extracts text, key/value pairs, selection marks (Checkboxes), tables, and structure from given documents.
SBI form Page 1-2

![alt text](https://github.com/Namrata-Agrawal/OCR-Recognition/blob/main/Recognition%20result/Recognized_form_page1.png)
![alt text](https://github.com/Namrata-Agrawal/OCR-Recognition/blob/main/Recognition%20result/Recognized_form_page2.png)
