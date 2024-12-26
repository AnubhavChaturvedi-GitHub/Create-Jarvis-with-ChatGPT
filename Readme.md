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

# Prompt 3 to open websites

---

**Python Script to Automate Google Search, Extract Websites, and Open in Browser**

The task is to create a Python script that performs the following actions:

1. **Accepts Input for Search Terms:** The script should take a list of search terms as input (e.g., "youtube", "instagram", "facebook", "telegram", "whatsapp").

2. **Automates Google Search:** For each of the input search terms, the script should automatically search for them on Google and extract relevant website URLs from the search results.

3. **Extracts Multiple URLs:** The script should efficiently extract a list of URLs from the Google search results. The number of results should be customizable, based on the user's needs.

4. **Opens URLs in Browser:** The extracted URLs should be automatically opened in a web browser.

5. **Handles Dependencies Smoothly:** The script should ensure all necessary libraries are installed by automating the installation process using `subprocess` for `pip`. This ensures that the required packages are installed without manual intervention, leading to faster execution.

6. **Optimization and Efficiency:** The script should be efficient, able to handle multiple search terms, extract URLs, and open them in the browser in a smooth and fast manner.

### Requirements:
- The script should handle the installation of libraries like `requests`, `BeautifulSoup4`, and `webbrowser` (or other dependencies if needed) in an efficient manner.
- Make sure the code runs on various environments by ensuring smooth installation and compatibility with the latest versions of the libraries.

### Libraries to Use:
- `requests` for making HTTP requests.
- `BeautifulSoup` from `bs4` for parsing the HTML and extracting URLs from the Google search results.
- `webbrowser` for opening the extracted URLs.
- `subprocess` to automate the installation of dependencies via `pip`.

**Expected Functionality:**
1. Accept input terms.
2. Perform a Google search for each term.
3. Extract and store multiple URLs.
4. Open each URL in the default web browser.
5. Automatically install necessary libraries if not present.

---

