# Auto-Vision-Scanner

        
        ## Classes:
                - Detect_Image: The class for analyzing the image given by the user.


        ## Functions:
                - 'detect_image()': For Analyzing the image
                

        ## Variables.
                - 'content' : the image matrix
                - 'image' : The type of the image which will portray the content
                - 'text_response' : The text contained in the image with other features like location of the text
                - 'predictions' : prediction for the image type
                - 'face_response' : Respone of the face(features of the face) after detecting face
                - 'face_content': Face Annotations
                - 'conf': The confidence of the prediction of the emotions
                - 'face_content_result': The likelihoof of all the emotions
## How we build:
We used the Google Clould Vision API,  Flask ,Python,  HTML to host it on the web page page.

## Running the Codes

Run command `python main.py` on Anaconda Prompt

The folder named "images" will contain the images which you will upload/import.





## Results

* For Facial Emotion Recognition: It is giving the likelihood of all the emotions like: joy, sad, surprise, 
* For Text type image: It will give the deatailed analysis of the image for example about the receipt of grocery store. It will give the 
amount spent on each item.



