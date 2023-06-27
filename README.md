
# BizCardX-Extracting-Business-Card-Data-with-OCR

BizCardX is a Python application that uses OCR  to extract data from business cards. It allows users to upload an image of a business card and extract relevant information such as name, designation, company name, contact details, email, website, address, and pincode.
1.extract data from business card image and text image.
2.Analyse extracted data and store it into the database
3.View and delete data
## Workflow
step1:Install the required packages !pip install -q streamlit !pip install easyocr !pip install sqlalchemy !pip install streamlit-option-menu ! !pip install sqlconnector import libraries easyocr streamlit pymong pandas cv2  numpy.

step2:Create streamlit app to extract text from the image 1.Upload language list document 2.Create connection to database

step3:In Streamlit App: 

1.Upload image of English language business card or other language business card
2.Click extract button
3.Text in the card will be extract and stored in database

step4: Others
1.Upload image of English language text image or other language text image
2.Choose the language of uploaded file
3.Click extract button
4.Text in the card will be extract and stored in database
5.Extracted data will be translate to English language

step5:Select the ML alogrithms to use the data which the tagert variable in siutable.

step5: Manage data

1.Selectbox lists all docments in database
2.View selected document
3.Delete the document

