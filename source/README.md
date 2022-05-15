
firstly clone the project using the following git repository

the software required is Matlab .

pls, make sure the matlab is installed in the systems.

now open the matlab and choose the following cloned folder directory 

Firstly , add the image or pdf you want to do the directory.

now if its the pdf format-

firstly open the " PDF_2_IMAGE_CONVERTOR.m " and add the pdf name inside the file and run 

now this PDF_2_IMAGE_CONVERTOR will convert your pdf of n number of pages in to n images 

if its shows any error in the process then download the computer vision toolbox in matlab as shown in the suggestion .

the converted files will be of format
" srikar.pdf-Page1.png"

Now , to do the ocr , we can use any type of image format like jpg ,png ,tif etc...

Now open the OCR_MAIN.m file and give the image name for which you want to detect the OCR 

NOW run the file OCR_MAIN.m the outputs are as shown 

this is the normal image of the uploaded file

![result#1](https://user-images.githubusercontent.com/99079411/168469828-c545a4ca-026c-4d69-b06c-54a373e49c07.jpg)
 
the OCR obtained will be displayed on the Commond window as well as stored in the file name finalresult.txt

"
KYRI E
PETRAKIS

GRAPHIC DESIGNER

Sed ut perspiciatis unde omnis iste nat
voluptatem accusantium doloremque Iaudantium,
totam rem aperiam, eaque ipsa quae ab illo

inventore veritatis et quasi.

CON ACT WORK EXPERIENCE

+123—456—789O 2012 _ 2013

he||o©rea|| reatsitecom ‘
9 L V9 Project Manager

® www.rea|| "

the confidence of each word detected can be seen as shown

![result#2](https://user-images.githubusercontent.com/99079411/168469913-dccb5dc6-0aa9-4ed8-8e71-ab83c998bf40.jpg)

to detect the face present in the document we use rectanglar box to detect exact face and we will crop the face and save the face.
as shown :

![result#3](https://user-images.githubusercontent.com/99079411/168469955-3b251274-0c54-4e32-9949-652df9194272.jpg)

![detectedface](https://user-images.githubusercontent.com/99079411/168469963-1007ab6e-02f8-4601-8ea4-43fd2eb0e3f7.jpg)

this is the following idea and steps of the OCR .



