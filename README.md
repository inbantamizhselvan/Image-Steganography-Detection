# Image-Steganography-Detection
README
Image Steganography Detection :

Image Steganography Detection is a project built using python programming on Jupyter notebook.

Loading the Project :

* Download the whole folder without missing any file from Github repositary.
* Start Anaconda Navigator and launch Jupyter Notebook. If you dont have Anaconda Navigator installed in your computer already, download it here https://www.anaconda.com/download .
* Since this is a project built with python make sure that python is installed in your computer, or download it from here https://www.python.org/downloads/ .
* In Jupyter Notebook click on file ==> open notebook and open the notebook named Image Steganography Detection.ipynb from the downloaded set of files.
* The python code requires some of the libraries such as openCV, tensorflow, keras, numpy, sklearn and matplotlib using pip install <package name> on Jupyter Notebook.
* Download the Trained model lsb_steganography_model.h5 here, https://drive.google.com/file/d/1r4htfkiGxTr5Q4WxTjj-Y2Fk-yh_r8pT/view?usp=drive_link

Execution and Result :

* Now you will find two cells of code. One is building a model and another one is to uploading the input to compare with the trained model to display the result.
* In the first cell provide respective path to the dataset images to access them, clean and stego which could be found on the dataset folder of the downloaded project. Replace these file paths with the respective paths of your dataset.
   clean_data, clean_labels = load_dataset('Downloads/archive-2/test/test/clean', 0)
    stego_data, stego_labels = load_dataset('Downloads/archive-2/test/test/stego', 1)
* The above process should be done only if you want to train the model again or else you can use the model already built lsb_steganography_model.h5, dont run anything since the model is already trained and saved.
* On the second cell replace the input file path image_path = 'Downloads/archive-2/test/test/clean_sample.png' with the file path of the input image which you want to test. You can use images on  the sample input folder in the downloaded project files.
* Save and run the code, you will get the result.
