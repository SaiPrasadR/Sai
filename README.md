**Title of 1st Project ** : C Image Steganography

**Created by  **         : Sai Prasad R

**Project Description ** : The project is all about hiding the Secret text into a image(encoding)
		       Retrieving the text / secret message from the processed image(decoding). 
		       First comes Magic String, then encoding file extension type(eg. .txt),
		       file extension size, total secret message size and then encoding the actual
		       message. For decoding the secret text, same process is followed by identifying                   the magic string
		       This can be achieved by storing each bit onto LSB to form a secret text.

Compiler used 	     : GCC Compiler

**(To Encode Secret file into image)**
Execution Command     : ./a.out -e beautiful.bmp[Image] secret.txt[File contains secret message] [stego.bmp]

Sample Ouput(Encoding) : Selected encoding
			 Read and validate encode arguments is success
			 Opened files successfully
			 Check capacity is success
			 Copying bmp header successful
			 Magic string is encoded successfully
			 Encoded secret file extension successfully
			 Encoded secret file size
			 Encoded secret data successfully
			 Copied Remaining image data successfully
			 Encoding is successful
    
**(To Decode Secret file from image)**

Execution Command    : ./a.out -d stego.bmp(Image contains secret text) [decode.txt](Secret message stored in file)

Sample Ouput(Decoding) : Selected decoding
			 Read and validate decode arguments is success
			 Opened files successfully
			 Str is #*
			 Magic string decoded successfully
			 value of b is 4
			 Extension size of file Decoded Successfully
			 the file extension is .txt
			 File extension decoding done successfully
			 value of file size is 25
			 Secret file size decoded successfully
			 Secret data decoded Successfully
			 Decoding is successful
    

**Title of 2nd Project**  : Inverted Search using Hashing Method

**Created By **   : Sai Prasad

**Description  ** : This project is based on the concept of Inverted Index Search.
		That is List of indexes of all the unique words were mapped to a
		document search. Concept of Hashing, File Handling, Strings
		were used. Project under the category of Data Structures.
