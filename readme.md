#### This project can be used in different organizations where customers or users need to provide any kind of id in order to get themselves verified. The organization can use this project to find out whether the ID is original or fake. Similarly this can be used for any type of ID like adhar, voter id, etc.
#### Finding out structural similarity of the images helped us in finding the difference or similarity in the shape of the images. Similarly, finding out the threshold and contours based on those threshold for the images converted into grayscale binary also helped us in shape analysis and recognition. 
#### Finally we visualized the differences and similarities between the images using by displaying the images with contours, difference and threshold.  

<img src="https://github.com/Mobolaji-Github/Pan-Card-Tampering-Flask-App/blob/master/app/static/generated/image_original.png?raw=true">
<img src="https://github.com/Mobolaji-Github/Pan-Card-Tampering-Flask-App/blob/master/app/static/generated/image_uploaded.jpg?raw=true">



Step to run application:
Step 1:	Create the copy of the project.
Step 2: Open command prompt and change your current path 
to folder where you can find 'app.py' file.
Step 3: Create environment by command given below-
conda create -name <environment name>
Step 4: Activate environment by command as follows-
conda activate <environment name>
Step 5: Use command below to install required dependencies-
python -m pip install -r requirements.txt
Step 6: Run application by command;
python app.py
You will get url copy it and paste in browser.
Step 7: You have sample_data folder where you can get images to test.
