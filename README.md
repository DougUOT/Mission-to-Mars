# Mission-to-Mars

## Overview of Project

We will help a junior data scientist to write a script that will gather all the information in one convenient location. We will gather data about the mission to Mars from all over the web and display it in a central location without manually gathering the data. In order to do that, we will build a web application that will scrape new data every time we click a button. We will write a Python script to navigate the web pages to collect the correct information. After this process, we need a place to store it. Instead of using an SQL database with its structural rules, we will use a NoSQL database MongoDB. We will be downloading tables, paragraphs and images. After that, we will put it all together in a web application of her own; for that reason, we will need to use Flask. Flask is a web framework that allows us to create a web application using Python and then customize it with HTML and CSS.

This assignment is related to the Bootcamp Data Analytics from the University of Toronto and comprises the goals below for this module: 

Follow below the goals for this module:

1) Objective 1: Scrape High-Resolution Mars Hemisphere Images and Titles
2) Objective 2: Update the Web App with Mars Hemisphere Images and Titles
3) Objective 3: Add Bootstrap 3 Components

## Resources

* Data Source: [Mission_to_Mars_Challenge.ipynb](https://github.com/DougUOT/Mission-to-Mars/blob/main/Mission_to_Mars_Challenge.ipynb), [scraping.py](https://github.com/DougUOT/Mission-to-Mars/blob/main/scraping.py), [app.py](https://github.com/DougUOT/Mission-to-Mars/blob/main/app.py) and [index.html](https://github.com/DougUOT/Mission-to-Mars/blob/main/templates/index.html)
* Software & Data Tools: Jupyter Notebook 6.4.6, Visual Studio Code 1.63.2, Python 3.8.8, MongoDB 4.11.0, Flask 1.1.2, Pandas 1.3.4, Bs4 4.10.0, MongoDB 5.0.5 and PyMongo 4.0.1

## Results & Code

### Objective 1: Scrape High-Resolution Mars Hemisphere Images and Titles

1.1) Make a copy of your Mission_to_Mars.ipynb file, and rename it Mission_to_Mars_Challenge.ipynb.

![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image1_1.PNG)

1.2) Download the Mission_to_Mars_Challenge_starter_code.ipynb, copy the starter code, and paste at the end of your Mission_to_Mars_Challenge.ipynb file.

![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image1_2.PNG) 

1.3) In Step 1, use your browser to visit the Mars Hemispheres (Links to an external site.) website to view the hemisphere images.

![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image1_3.PNG)

1.4) Use the DevTools to inspect the page for the proper elements to scrape. You will need to retrieve the full-resolution image for each of Mars's hemispheres.

![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image1_3_1.PNG)
![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image1_3_2.PNG)

Full-resolution image URL string and title for each hemisphere image: Cerberus Hemisphere Enhanced

![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image1_3_3.PNG)

Full-resolution image URL string and title for each hemisphere image: Schiaparelli Hemisphere Enhanced

![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image1_3_4.PNG)

Full-resolution image URL string and title for each hemisphere image: Syrtis Major Hemisphere Enhanced

![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image1_3_5.PNG)

Full-resolution image URL string and title for each hemisphere image: Valles Marineris Hemisphere Enhanced

![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image1_3_6.PNG)

### Objective 2: Update the Web App with Mars Hemisphere Images and Titles

2.1) The scraping.py file contains code that retrieves the full-resolution image URL and title for each hemisphere image

![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image2_1.PNG)
![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image2_1_1.PNG)
![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image2_1_2.PNG)

2.2) The Mongo database is updated to contain the full-resolution image URL and title for each hemisphere image

![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image2_2.PNG)
![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image2_2_1.PNG)

2.3) The index.html file contains code that will display the full-resolution image URL and title for each hemisphere image

![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image2_3_1.PNG)
![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image2_3_2.PNG)

2.4) After the scraping has been completed, the web app contains all the information from this module and the full-resolution images and titles for the four hemisphere images

Page one

![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image2_4_1.PNG)

Page two

![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image2_4_2.PNG)

### Objective 3: Add Bootstrap 3 Components

3.1) The webpage is mobile-responsive

The webpage is mobile-responsive and the image bellow showing on a Galaxy Fold device, follow below the pages from one to three.


![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image3_1_Mobile%20version%20Galaxy%20Fold_pag1.PNG)
![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image3_1_Mobile%20version%20Galaxy%20Fold_pag2.PNG)
![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image3_1_Mobile%20version%20Galaxy%20Fold_pag3.PNG)

3.2) Two additional Bootstrap 3 components are used to style the webpage

Changed the background image and add the yellow color on title of the web site Mission to Mars. Follow below code & image

![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image3_2_2_Two%20add%20style%20code.PNG)
![](https://github.com/DougUOT/Mission-to-Mars/blob/main/Resources/Images/Mission%20to%20Mars%20image3_2_2_Two%20add%20style%20background%20and%20title%20color.PNG)
