# First Prompt 1 ( STT )

---
Write a Python script that recognizes speech using the `speech_recognition` module while automating the installation of required packages via the `subprocess` module. Ensure the script uses advanced configurations of `sr.Recognizer` for optimal performance. Implement and configure the following parameters to achieve the fastest and most accurate results:


r = sr.Recognizer()
r.dynamic_energy_adjustment_damping = 0.3
r.dynamic_energy_ratio = 0.9
r.dynamic_energy_threshold = False
r.pause_threshold = 0.5
r.operation_timeout = None
r.non_speaking_duration = 0.5


Ensure the script demonstrates fast and efficient real-time speech recognition by handling background noise and optimizing speed. 

---

# Second Prompt 2 ( TTS )

---

Create an optimized and advanced Python code for text-to-speech using the pyttsx3 library. The code should be fast and efficient. Use the subprocess module to automate the installation of required dependencies with pip. Implement a function named speak that accepts text and converts it to speech. Within the function, vary the pitch of the speech randomly. Additionally, allow the user to set the voice property by using the voice ID

---

# Prompt 3 to open multiple websites

---
Create a Python script that automates the process of searching Google for a list of terms and opening the top results in a web browser. The script should include the following steps:

Library Installation:

Check if the required library googlesearch-python is installed. If not, automatically install it using pip.
Google Search Functionality:

Define a function to perform a Google search for each search term and return the top results.
Allow the number of search results to be configurable (default: 5).
Opening URLs:

For each search term, open the top URLs in the web browser.
The script should open the URLs one by one.
Main Automation:

The script should take a list of search terms, search Google for each, display the found URLs, and open the results in a web browser.
Example Usage:

Provide an example usage with a list of search terms (e.g., ‘youtube’, ‘instagram’, ‘facebook’, etc.).
---

# prompt 4 open multiple apps

---

Create a Python script that allows users to open multiple applications by specifying their names. The script should be able to open applications on different platforms (Windows, Linux, and MacOS) and handle errors gracefully. The script should:

1. **Accept user input:** Ask the user to input a list of application names (separated by space).
2. **Split the input into individual app names:** Handle the input as a space-separated string and split it into a list of applications.
3. **Platform-specific app launching:**
    - For **Windows**: Use the `start` command to open apps available in the system's PATH or specify full paths.
    - For **Linux**: Attempt to open apps directly by calling their executable names (if they are in the PATH).
    - For **MacOS**: Use the `open` command to open apps.
4. **Error handling:**
    - Handle the case where the app is not found by printing an appropriate error message.
    - Catch and report any exceptions that occur during the execution (like issues with permissions, invalid app names, etc.).
5. **Feedback:** Print a message when each app is successfully opened or if there is an error.
6. **Exit gracefully:** If no apps are entered, print a message and exit.

The script should use Python's `subprocess` module to run system commands and handle exceptions. The main program should run only if the script is executed directly (i.e., `if __name__ == "__main__":` block).

**Additional Requirements:**
- Ensure the code works on **Windows**, **Linux**, and **MacOS**.
- Provide clear error messages when things go wrong, such as when an app is not found or when the command execution fails.
- Include checks for unsupported platforms.
- Provide an example of usage, such as asking the user to input apps like "chrome firefox vscode" or "safari terminal".

---

