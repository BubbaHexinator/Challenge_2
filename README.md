# Loan Qualifier App

## Directory ##

[daily_rate_sheet.csv](data)

[images](images)

[filters](qualifier/filters)

[utilites](qualifier/utils)


*Welcome to my Loan Qualifier App*

*USER-STORY*\
As a application manager for a local fintech startup I wanted to create an app that would allow borrowers the ability 
to determine if they were elligible for a loan. I wanted to create an app that would make the user experience as easy as possible by using CLI. In order to maintain the stability of the app I needed to modulize the app.  In In this READme, I will outline what inspired me to do this project along with the different attributes that make this app so successfull. 

*Software Requirments:*\
-Python package installed.\
-instll fire and questionary to local.

As a young professional I have slowly been more interetested in my financials. The key to making this app was to make it as user friendly as possible. The main problem that inspired me to do this was the lack of user-friendly financial interfaces on the market that could gave the user a qick answer for a loan approval. With this tool a user can easily manage, locate and source possible loans given by a list of poplular banking institutions. 

---
## Technologies
The program is made on python version 3.9.12. The libraries included in the project are Fire and Questionary and import pathlib. The operating system is Windows 10. The programing interfaces used for writing code was VS code. You can run the code by running the file *app.py* in your terminal. The recommend running Gitbash in order to run the file but the provided termainal in VS code is just as good. 

*Modulizing*\
It was important for me to keep this app running as smooth as possible and in order to do that I had to modulize it.  Modulizing is done by placing pieces of code into different modules or python files(.py files) which allows the application to run as one, by importing code or calculations from different modules.  By doing this enables the code to stay intact, reduce the headache of re-writing code and creates a cleaner, nice and neat work space.  I began modulizing my code by making two subfolders within the qualifier directory; filters and utils. These folders house the brunt of the coding.  In each respected directories I inserted, and hashed out, in each .py file, a line of code at the top that says what the module does and its purpose in regards to how it interacts with the app.py file as a whole. Next I made a images and data folder, each in the loan_qualifier_app directory. The [images](images) folder houses all the images i used for the READme file. The [daily_rate_sheet.csv](data) holds the *daily_rate_sheet.csv*

*What is CLI?*\
In order to ensure userability It was important for me to makes the applicatino run as smoothly and operateable as possible. 
because polished developers would be testing this app, but also novice new devopomers, even people with no experience. In order to make this user friendly it was important for me to make a Command line Interface (CLI). A CLI allows a user to run or operate a module with no advanced fintech knowledge or coding experience.  Key concepts, words like variables or parameters, concepts for someone with no expeirce. for example, are not needed because the user can interact with the module in a user friendly experience. By importing this practice, I can take into consideration how the user must feel when taking a look at new code, or at least running it. Someone can feel overwhelmed when tasked to do something new, so by refereing a CLI a user can easily navigate through a modue. 

By modulizing my code I can help user better comprehend my overal working environment. This strategy is used in almost all coding professional work spaces and thus is why it was important for me to incorporate into my Loan Qualififer App. 


*Quesitonary and fire*\
The last thing you need to do is to make sure you have quesiton and fire dependcies installed in your terminal. In order to run this app at the CLI you need these installed. Also please make sure you have the correct path copied and written down for the CSV file. The first prompt the app warns you is "What is the path of the csv file"?. Please located the location of the csv file and copy and paste the path here. This will allow the interface to gather important information from the CSV file, otherwise the code will not work. I put this in as a variable so in the future if a user wants to import another CSV file they can do so. For example, if there are a list of potential loans from other banks, the user could import that information into another CSV file, of course with the same columns names and headers and run the script and get intriely different outcomes. Prety neat!

---

## Installation Guide


Please install *pip install questionary* and *pip install fire*. You need these dependencies in order to run the app.py. As far as Pandas goes, the user should already have Pandas installed however, if Pandas is not installed, please type *pip instal pandas*

Asumming you have python and anaconda installed your next step is to activate your dev environment. First go ahead and open the Gitbash terminal in VS code. Type *conda activate* and then *conda activate dev* . ![Activate Dev environment.](images/conda_activate_dev.png)
This will let the computer know that you want to be in a developer enviroment in your terminal. As a developer you can runs scripts of code, import library and dependencies and much more.  

Next you will need two libraries installed in order to run app.py; Fire and Questionary. Take a look at the screen shot below to see how I installed them in order.  
![Install Questionary.](/Challenge_2/loan_qualifier_app/Images/install_questionary.png)

Install Fire
![Install Fire](/Challenge_2/loan_qualifier_app/Images/install_fire.png)

---

## Usage
This section should include screenshots, code blocks, or animations explaining how to use your project.Now its time to run the script. 


In gitbash or your terminal navigate to your present working directory where your app.py file is located. In this example the app.py file is located in the loan_qualifier_app directory. Next, in the Command line Interface, in your terminal,  type *python app.py*

This is how it should look ![running python app.py in Gitbash terminal within VS code](/Challenge_2/loan_qualifier_app/Images/running_python_app.png)

Next, a question will appear and prompt you to type (copy and paste, if it's easier) the csv file path for the daily_rate_sheet. 

Here is a screen shot of how many loans you may qualify for with a credit score of 700, a monthly debt of 100, total monthly income of 4500, desired loan amount of 50000 and your home value of 400000. ![running script](/Challenge_2/loan_qualifier_app/Images/app.png)

In this example I had 11 qualifying loans. This data could change though if you were to change certain peramiters. For example if the I changed the credit score to 500 and kept the the rest of the parameters the same from the previous example, I would get the following results. ![new running script](/Challenge_2/loan_qualifier_app/Images/adjust_run_app.png). As you can see from the photo,  with a credit score of 500 I am now qualified for zero loans. Pretty cool right!


---

## Contributors

I am the sole contributor for this project. all scripts and promts were coded by me with help of my fintech boot camp. 

---

## License

When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.

All rights are reserved. MIT. No part of this code may be reproduced, distributed, or transmitted in any form by any means without prior written permission of the publisher. 
