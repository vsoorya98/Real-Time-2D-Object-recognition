The operating I used is Macos Ventura and I used Clion as my IDE



Instructions for running the executables:

Note: Once you download all the .cpp and .h files, create three new folders named driver, infer, train
       place the main.cpp and test.cpp in the driver folder
       place the Classifier.cpp and .h in the infer folder
       place the feature.cpp and .h, trainingData.cpp and .h in the train folder
       place the rest of the files in the main folder, also name the main folder as 'CV' or you will have to make changes in the CMakeLists.txt file (if you do not follow the above steps )


Instructions for testing my code:

we have two main modes Training and inference mode

When you want to enter the object name press the respective object label number to store the object name into the CSV file
When the user presses 'S' or 's' it saves the frame
It also asks for the image name to be saved
When the user presses the 'Q' or 'q' the program quits
Press 'B' or 'b' for Thresholding
Press 'M' or 'm' for Morphological processing
Press 'C' or 'c' to apply color to the regions
Press 'N' or 'n' for training mode
Press the label respective number to select that object and name it
Press 'W' or 'w' to save the CSV file once you have labeled all the parts
Press 'I' or 'i' for inference mode

EXPECTED OUTPUT :

When you press 'n/N' it goes into training mode, select objects by entering their label number once you are done save the CSV file by pressing 'W/w'
when you press 'I/i' it goes for interference mode, it should display the objects that are similar to the object placed before


