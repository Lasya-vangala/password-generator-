Password Generator


Description

The Password Generator is a Python-based project designed to generate strong and secure passwords based on user preferences. This project helps enhance security for online accounts, applications, and other authentication systems. It allows users to define password length and choose whether to include letters, numbers, and special characters. The project is implemented using Python, leveraging libraries such as random for generating random characters and string for handling character types. The program provides a simple command-line interface, making it easy to use.


Features

1.Generates strong passwords based on user-defined criteria.

2.Customizable options to include letters, numbers, and special characters.

3.Ensures at least one character type is selected before generating a password.

4.Lightweight, simple to use, and runs through a command-line interface.

5.Avoids common and weak password patterns for better security.


Technologies Used

1.Python: Primary programming language for the project.

2.random module: Used to generate random characters for passwords.

3.string module: Provides access to different character sets.


How to Run

Running in Jupyter Notebook

1.Ensure you have Jupyter Notebook installed. If not, install it using:

   pip install notebook

2.Download or clone the repository:

   git clone https://github.com/Lasya-Vangala/password-generator.git

3.Navigate to the project directory and launch Jupyter Notebook:

   cd password-generator
   jupyter notebook
   
4.Open password_generator.ipynb and run the cells to generate a password.

   

Running as a Python Script

1.Convert the Jupyter Notebook to a Python script (if not already done):

    jupyter nbconvert --to script password_generator.ipynb

2.Run the script:

    python password_generator.py



Procedure for Using the Password Generator

1.The program will ask for the length of the password.

2.The user is prompted to specify:

   2.1 Whether to include numbers.

   2.2 Whether to include special characters.

   2.3 Whether to include letters.

3.If the user selects no for all options, an error message appears, and the user must select at least one character type.

4.Once valid inputs are provided, the program generates a secure password and displays it.

5.The user can re-run the script to generate another password if needed.


screenshots

Screenshots are available in the [screenshots folder](screenshots/).