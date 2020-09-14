# Accesing-to-instagram-from-facebook-login-with-Selenium-and-Python

How to run selenium in windows

You can download Python bindings for Selenium from the PyPI page for selenium package. However, a better approach would be to use pip to install the selenium package. 
Python 3.6 has pip available in the standard library. Using pip, you can install selenium like this:

> pip install selenium

You may consider using virtualenv to create isolated Python environments. Python 3 has venv which is almost the same as virtualenv.
---------------------
Selenium requires a driver to interface with the chosen browser. Firefox, for example, requires geckodriver, which needs to be installed before the below examples can be run. 
Make sure it’s in your PATH, e. g., place it in /usr/bin or /usr/local/bin.

Failure to observe this step will give you an error selenium.common.exceptions.WebDriverException: Message: ‘geckodriver’ executable needs to be in PATH.

Other supported browsers will have their own drivers available. Links to some of the more popular browser drivers follow.

> Chrome:	https://sites.google.com/a/chromium.org/chromedriver/downloads

> Edge:	https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/

> Firefox:	https://github.com/mozilla/geckodriver/releases

> Safari:	https://webkit.org/blog/6900/webdriver-support-in-safari-10/

---------------------
Detailed instructions for Windows users
Note
You should have an internet connection to perform this installation.

Install Python 3.6 using the MSI available in python.org download page.

Start a command prompt using the cmd.exe program and run the pip command as given below to install selenium.

> C:\Python35\Scripts\pip.exe install selenium

Now you can run your test scripts using Python. For example, 
if you have created a Selenium based script and saved it inside C:\my_selenium_script.py, you can run it like this:

> C:\Python35\python.exe C:\my_selenium_script.py

----------------------------

