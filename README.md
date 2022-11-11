# Zhongke-Wenge-Internship-Report

The original code framework will not be uploaded due to its large footprint (including many models and datasets). The detailed report of the training results can refer to the docx file.

## Internship Content
1. Conducted detailed research and records on common technologies in the field of OCR and the use of paddleOCR's framework.

2. Test the effect of paddleOCR's English print recognition and table recognition using real scene pictures, and analyze the problems in its default detection model in detail. It is found that the background interference of pictures, too dense text, and bent text boxes are the main reasons for poor text detection and recognition.

3.Find a solution to the problem of poor text detection and recognition caused by the bending of the text box. After comparison and analysis, I select the SAST detection model and use the Total-Text dataset for training and testing. Finally, the prediction result of this model exceeded the accuracy rate of default model by 27.83% on average.

4.Discover and communicate with the developers of Zhongke Wenge about the shortcomings of the paddleOCR framework: On the basis of using the SAST detection model, the paddleOCR framework does not support further identification.
