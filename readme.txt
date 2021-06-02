Project to read text from images using Microsoft Azure Computer Vision cognitive service.

There are two APIs available in Azure Cognitive Services for reading text from images :
	1. OCR API
	2. Read API

The OCR API is an optical character recognition API that is optimized for reading small to medium amounts of printed text in .jpg, .png, .gif, and .bmp format images. It supports a wide range of languages and in addition to reading text in the image it can determine the orientation of each text region and return information about the rotation angle of the text in relation to the image.

The Read API uses a newer text recognition model than the OCR API, and performs better for larger images that contain a lot of text. It also supports text extraction from .pdf files, and can recognize both printed text (in multiple languages) and handwritten text (in English). It uses an asynchronous operation model, in which a request to start text recognition is submitted; and the operation ID returned from the request can subsequently be used to check progress and retrieve results.

In this project we can read the text from the images using both the APIs based on user's choice.
The resultant image is stored in the "output" folder and the results are also written into the "output.txt" file.