# How To Running this Project

##  Libraries

1. **selenium**: for web automation and browser interaction
2. **bs4 (BeautifulSoup)**: for extracting data from static websites
3. **requests**: for sending HTTP requests and retrieving web content
4. **re**: for text manipulation using regular expressions
5. **os**: for creating and managing files and folders
6. **time**: for handling delays and time-related operations
7. **pandas**: for data manipulation and analysis
8. **numpy**: for numerical operations and array processing

##  Setup Python and Environment

1.  Download and install Python from the official website.
    - Open Command Prompt (CMD) to check whether Python is installed correctly.
    - Type `python --version`.
    - If a Python version number appears, Python is successfully installed.
2.  Open Visual Studio Code (VS Code).
3.  Open or create a new folder in VS Code to store this project.
4.  Open the Terminal in VS Code.
5.  In the terminal, type:
    ```python -m venv scraping-env``` 
    This will create a virtual environment inside the project folder.
6. Create or open a Python file with the `.ipynb` extension.
7. After opening the file, click **Select Kernel** in the top-right corner and choose the virtual environment you created earlier.

##  Setup Library and Running Project

1.  Open the terminal and run:
    `pip install -r requirements.txt`
    This command will installs all libraries used in this project.
2.  Run the code in the file "scraping_wikipedia.ipynb".
3.  After that, run the code in the file "scraping_gmaps_with_checkpoint.ipynb".
4.  The results will be saved in this files.