------------------------------------------------------------
Youtube Link : https://www.youtube.com/watch?v=qIFjimwo4hk
------------------------------------------------------------


 CS50P-Final-Project-Date-Converter
-------------------------------------

 Introduction
 -------------
The English-Nepali Date Converter is a Python-based tool designed to seamlessly convert dates between the Gregorian Calendar (AD) and the Nepali Bikram Sambat (BS) calendar.
 This project was developed as part of CS50P: Introduction to Programming with Python,
 a course that emphasizes foundational programming skills, problem-solving, and practical application .
The converter not only handles date conversions but also ensures accessibility by supporting bidirectional
 language translation (English ⇄ Nepali). Built within the CS50 IDE,this project meets all the requirements outlined for the final project while addressingreal-world challenges faced by users in Nepal and beyond.


 Project Overview
 -----------------
This project demonstrates the power of Python to solve complex problems through logical algorithms and structured code. It converts dates between AD (Gregorian) and BS (Bikram Sambat) calendars using custom-built algorithms that account for unique calendar structures, such as varying month lengths and leap-year rules specific to the Nepali calendar .
 Additionally, it provides error handling and input validation to ensure robust performance, making it both user-friendly and reliable.



What’s Inside the Project
--------------------------------
1. Core Functionality

     - Date Conversion:
     -Converts dates between AD (Gregorian) and BS (Bikram Sambat) calendars
     using custom algorithms that account for:
     - Nepali calendar month structures (e.g., varying month lengths like Baishakh having 30/31 days).
     - Leap-year rules specific to the BS calendar.

     This feature makes the tool accessible to users unfamiliar with either language, bridging cultural and linguistic gaps .


2. Validation & Error Handling
   - Ensures invalid dates (e.g., February 30) are rejected .
   - Validates user inputs to prevent crashes.

    These safeguards make the tool resilient to errors and user mistakes, enhancing its usability.


3. What Can It Do?
   - Solve Real-World Problems:

  - The Nepali calendar is widely used in Nepal for festivals,
    government documents, and cultural events. This tool automates
    error-prone manual conversions, saving time and reducing mistakes .

  - Language Accessibility:
    By supporting bidirectional language translation, the converter enables users unfamiliar with the Nepali language to interact with BS dates (and vice versa).
    This is particularly useful for international organizations, travelers, or anyone working across cultural boundaries.


  - Educational Value:
     The project demonstrates practical applications of Python for calendar algorithms and localization.
     It showcases how Python can be used to solve niche problems with precision and clarity.



I have met all the requirements of this project. The Requirements are as Follows:
---------------------------------------------------------------------------------

Your project must be implemented in Python.

Your project must have a main function and three or more additional functions.

At least three of those additional functions must be accompanied by tests that can be executed with pytest.

Your main function must be in a file called project.py, which should be in the “root” (i.e., top-level folder) of your project.

Your 3 required custom functions other than main must also be in project.py and defined at the same indentation level as main (i.e., not nested under any classes or functions).

Your test functions must be in a file called test_project.py, which should also be in the “root” of your project.

Be sure they have the same name as your custom functions, prepended with test_ (test_custom_function, for example, where custom_function is a function you’ve implemented in project.py).

You are welcome to implement additional classes and functions as you see fit beyond the minimum requirement.

Implementing your project should entail more time and effort than is required by each of the course’s problem sets.

Any pip-installable libraries that your project requires must be listed, one per line, in a file called requirements.txt in the root of your project.



How Does It Meet the CS50P Requirements?
-------------------------------------------------
The project adheres to all the requirements specified for the final project:

1. Implementation in Python:
   The entire project is implemented in Python, leveraging core libraries like `datetime` and `sys` without relying on external frameworks .

2. Main Function and Additional Functions:
   The project includes a `main()` function and three additional custom functions:
   - `convert_ad_to_bs()`: Converts AD dates to BS.
   - `convert_bs_to_ad()`: Converts BS dates to AD.
   - `validate_date()`: Validates user inputs to ensure correctness.

3. Testing with pytest:
   Each of the three custom functions is accompanied by test functions in a file named `test_project.py`. These tests ensure the reliability of the conversion algorithms and validation logic. For example:
   - `test_convert_ad_to_bs()`
   - `test_convert_bs_to_ad()`
   - `test_validate_date()`

4. File Structure:
   - The `main()` function and custom functions are defined in `project.py`, located in the root folder.
   - Test functions are stored in `test_project.py`, also in the root folder.
   - Any pip-installable libraries required by the project are listed in `requirements.txt`.

5. Effort and Scope:
   Developing this project required significant time and effort, surpassing the complexity of individual problem sets. It involved researching Nepali calendar rules, designing algorithms, implementing error handling, and writing comprehensive tests [[6]].


Why Use the CS50 IDE?
---------------------
The project was built entirely within the CS50 IDE, a cloud-based development environment that simplifies setup and execution. Key advantages include:
- Seamless Accessibility: Work from any device with an internet connection.
- Pre-configured Environment: No need to install dependencies locally; the IDE comes with Python and other tools pre-installed.
- Built-in Terminal: Execute Python scripts directly in the IDE, streamlining testing and debugging.

Using the CS50 IDE aligns with the course's philosophy of abstracting setup complexity to focus on problem-solving and coding .


Conclusion
-----------
The English-Nepali Date Converter is a testament to the power of Python and the principles taught in CS50P. By combining custom algorithms, robust validation, and multilingual support, the tool addresses a practical need while showcasing the versatility of Python. It meets all the course requirements, including modular design, testing with pytest, and adherence to file structure guidelines. Whether you're converting dates for personal use, professional tasks, or educational purposes, this project demonstrates how programming can solve real-world challenges effectively.

